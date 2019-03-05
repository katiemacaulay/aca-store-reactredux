## Intro
We have built a perfectly operational ecommerce web app. We are using webpack build tools to make our side even better. Now let's try implementing redux and react-redux in order to make it even better. Remember we are using the module system now so everything needs to be imported and exported. 

# Setup
* fork, clone, npm i, npm i react-redux

# index.js
* Import Provider from react-redux and wrap App with it.
* Give Provider a props called "store" with the value of the redux store.
* What is Provider?
* The provider is what allows each component to have access to the store automtically without us having to pass it down props to every child ourselves.

# ProductList.js
* Import connect from react-redux
* Remove the default export of the ProductList component
* mapStateToProps  - from the state products to the prop products
* connect the component to redux connect(mapStateToProps)
* Default export the connected component
* Does the ProductList component itself have any idea that redux exists?
