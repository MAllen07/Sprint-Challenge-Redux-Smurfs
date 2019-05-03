1.  Name 3 JavaScript Array/Object Methods that do not produce side-effects?
map , filter, reduce


 2. Which method do we use to create a new object while extending the properties of another object?
 map


3.  Describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
Actions: Functions that are invoked to pass along payloads of data that get sent from your app to the store and are the only source of information for the store.

Reducers: Specify how the state will change in response to actions. When they are called, they capture information and inject it into the state.

Store: The place where all of your state lives in a redux application. Store is known as a single source of truth because it holds our entire state tree and acts as a 'master state' for the application, allowing us to send state down as needed.

4.  What is the difference between Application state and Component state? 


When would be a good time to use one over the other? 

What is middleware?



1.  Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?


1.  Which `react-redux` method links up our `components` with our `redux store`?
