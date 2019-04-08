# Redux: Get State from the Redux Store
```javascript
const store = Redux.createStore(
  (state = 5) => state
);

// change code below this line
let currentState = store.getState();
