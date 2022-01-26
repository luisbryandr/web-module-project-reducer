# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* the event (click by user) triggers the onClick attribute of the button which is set equal to the equation "handleclick
* the handleclick function runs which is an annonymous function designed to use dispatch method from useReducer hook
* the dispatch method takes in the argument of the addOne action creator.
* causing the action creator to  fit in to the corresponding case scenario in the reducer function 
* thus the reducer function runs wih the current state and shoots out a new piece of state
* the new piece of state is then given by useReducer Hook which is prop drilled into the TotalDisplay component
* totalDisplay takes the state's total property value and renders to the UI
...

* TotalDisplay shows the total plus 1.
