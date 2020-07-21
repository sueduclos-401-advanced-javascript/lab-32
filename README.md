# Lab-32 - Class 32

Code 401 Class 32 Virtual Store Phase 3

## Project Name - Virtual Store app

Virtual Store Phase 3: Connect the Virtual Store to an API to retrieve live data from your data source, using thunk to enable asynchronous actions

In phase 3, we will be connecting our Virtual Store to a live API so that our data is persistent and able to be separately managed.

The user stories from Phases 1 and 2 remain unchanged. For this phase, we are now adding the following new user stories to meet the new requirements.

* As a user, I want to interact with live inventory so that I have confidence that the displayed products are in stock
* As a user, I want to know to that when I add an item to my cart, that it is removed from inventory so that no other users can purchase it

## Technical Requirements / Notes

* Continue to use Material UI Components for layout and styling
* Load the category and product list from a remote API on page load.
* Update the product quantity in stock when adding items to (or removing from) the cart
* Continue to use multiple reducers

* You will need to use useEffect() to dispatch a load action on the initial page load
  * This will need to use thunk as it will be asynchronous
* When adding/removing/updating items in the cart, the action/reducer will need to update the server
  * Perform the appropriate post, put, or delete action via API call (using thunk in an async action) on each of these actions as performed by the users

### Author: Sue Duclos

### Links and Resources

- [CodeSandox Link](https://codesandbox.io/s/lab-32-redux-asynchronous-actions-7yw3x)
- [Netlify Deployment](www.abc.com)

### Setup

* npm install
* npm install enzyme
