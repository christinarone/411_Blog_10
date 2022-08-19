# 411_Blog_10
Class 10
Discuss in words something you learned in class today or this week.
  I've been learning more about the interview problems. Redux is difficult to learn and I'm trying to get the hang of it.

What is Redux? 
  Redux is an open-source JavaScript library for managing and centralizing application state. It is most commonly used with libraries such as React or Angular for building user interfaces.
  
What is ‘Store’ in Redux?
  A store is an immutable object tree in Redux. A store is a state container which holds the application's state. Redux can have only a single store in your application. Whenever a store is created in Redux, you need to specify the reducer.

How is state changed in Redux?
  The only way to update a state inside a store is to dispatch an action and define a reducer function to perform tasks based on the given actions. Once dispatched, the action goes inside the reducer functions which performs the tasks and return the updated state to the store. This is what Redux is all about.

What is the difference between a Presentational component and a Container component?
  In React components are often divided into 2 big buckets: presentational components and container components.

Each of those have their unique characteristics.

Presentational components are mostly concerned with generating some markup to be outputted.
They don’t manage any kind of state, except for state related to the presentation. Container components are mostly concerned with the “backend” operations.They might handle the state of various sub-components. They might wrap several presentational components. They might interface with Redux. As a way to simplify the distinction, we can say presentational components are concerned with the look, container components are concerned with making things work.

What is the second argument that can optionally be passed to setState and what is its purpose?
  The second argument that can optionally be passed to setState is a callback function which gets called immediately after the setState is completed and the components get re-rendered.

Which (if there is) node library method could you use to solve the algorithm problem you solved last night in your pre-homework.
  I think the one that would work is Redux.

Which (if there is) node library method could you use to solve the algorithm problem you solved in class tonight?
  It would probably be Redux.

What is your opinion of currently popular frameworks/libraries? List and provide your thoughts.
  I think they are very useful when you know how to use them . For me, it's hard to understand because I'm a beginner at this. But I think for those who have more experience, the Redux framework/library is very useful to know and use.
