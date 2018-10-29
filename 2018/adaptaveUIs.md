# Reading the User's Mind with Adaptive & Intelligent UIs
#### [David Khourshid](https://www.npmjs.com/~davidkpiano)

## User behaviour is hard to predict
* Feedback group is usually co-workers, QA, and a few others
* How to capture all user's feedback
    * How to capture "stickyness"
    * Feedback loop takes a while
    * New version makes old analytics not useful
## [Guess.js](https://github.com/guess-js) (alpha)
## How to keep users from making unnessecary, resource intensive api calls
* Bottom up approach?
    * Put logic at the lowest level
    * Not scalable
    * Difficult to test
    * Difficult to enhance
## Finite state machines & State Charts
* Makes more sense
* Can store predicted state in object literals
    * `{searching: {blah}, loading: {blah1}, photo: {blah2}}`
* [xstate](https://www.npmjs.com/package/xstate) (made by the presenter)
    * Lots of good examples there
* Can be very powerful for testing
    * Really cool tic-tac-toe example
## Analysis by path weights
* Optimize the UI based on the path users take through the site
    * Analysis can be done with state charts
* Can use well known algorithms to find which paths will be visited most often
## Analysis by scoring actions
* Give UI elements a score based on the actions users take with them
    * Automatically using state charts
* UI decisions can be based on data instead of cloudy user feedback
## Each time there is a transition, track the state change and store it somewhere
* A transition can be similar to an action in redux
