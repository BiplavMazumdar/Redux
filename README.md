# Redux
we will learn about redux
#Redux is used for state management 
# we have to create react store 
# why redux
1. when javascript application grows big, it becomes difficult for the user to manage its state.

2. redux solves this problem by managing application state with a single object called store 

3. make testing ver easy

4.Consistency throught the application

$ Action and Reducer 

.1 An action is a plane object{key:val} that describes the intention to cause change 

.2 A reducer is a function(fn()) that determines changes to an application's state. return the new state and tell the store how to do.

.3 it uses the action it receives to determine this change.

Action -> reducer -> store -> view(UI) -> Action
