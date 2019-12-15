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

