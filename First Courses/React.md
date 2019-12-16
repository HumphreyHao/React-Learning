# React

start:
```
import React from 'react';
```

how to use the HTML/JSX:
eg:
```
import React from 'react';

export default class App extends React.Component {
  getGreeting() {
    return 'Welcome to React';
  }

  render() {
    return (
      <div>
        <h1>{this.getGreeting()}</h1>
      </div>
    );
  }
}

ReactDOM.render(
  <App />,
  document.getElementById('root')
);
```

### note that all React components need to start with a capital letter.

## React Props
things works like the attribution

## state
it is the status of the element
it can not be changed by"="
but can be changed with the function of setState()
setState() wiil invoke the render() function



