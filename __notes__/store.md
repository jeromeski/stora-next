
import { createStore } from 'redux'
#### createStore 
const store = createStore(todos, ['Use Redux'])

- Creates a Redux store that holds the complete state tree of your app. There should only be a single store in your app.

#### applyMiddleware
- Middleware is the suggested way to extend Redux with custom functionality. 

