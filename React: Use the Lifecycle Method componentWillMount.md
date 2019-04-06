# React: Use the Lifecycle Method componentWillMount
```javascript
class MyComponent extends React.Component {
  constructor(props) {
    super(props);
  }
  componentWillMount() {
    // change code below this line
    console.log("will mount method");
    // change code above this line
  }
  render() {
    return <div />
  }
};
