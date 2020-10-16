# Angular questions

1) **What are the advantages of typescript? give examples to features in ts.**
   - Code scalability with “Interface oriented development”
   - TypeScript helps you dealing with growing teams.
   - Types have a proven ability to enhance code quality and understandability.\
   features: interefaces.
2) **What is async pipe?**\
   The async pipe subscribes to an Observable or Promise and returns the latest value it has emitted. When a new value is emitted, the async pipe marks the component to be 
   checked for changes. When the component gets destroyed, the async pipe unsubscribes automatically to avoid potential memory leaks.    
3) **What is the difference between Subject and BehaviorSubject?**\
    A BehaviorSubject holds one value. When it is subscribed it emits the value immediately. A Subject doesn't hold a value.
4) **What is change detection?**\
    Angular includes a mechanism that detects change detection loops. In development mode, the framework runs change detection twice to check if the value has changed since 
    the first run. In production mode change detection is only run once to have a better performance. 
5) **What is the difference between switchmap and mergemap?**\
   switchMap cancels previous HTTP requests that are still in progress, while mergeMap lets all of them finish.
