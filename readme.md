# My Demo UI Library

This is a demo UI component library created using React, TypeScript, Rollup, Storybook, Jest, and React Testing Library. It was created as part of an article for LogRocket on how to create a UI component library in React. You can read the article [here](https://blog.logrocket.com/build-component-library-react-typescript/).

## Installation

You can install this demo UI library using npm:

```
npm install @timonwa/ui-library-demo
```

## Usage

To use this demo UI library in your project, import the components you need from the library and use them in your React components.

```jsx
import React from "react";
import { Input, Button } from "@timonwa/ui-library-demo";

function App() {
  return (
    <div>
      <Input
        id="name"
        disabled={false}
        label="Enter your name"
        message="This field is required"
        error={false}
        success={false}
        onChange={(e) => console.log(e.target.value)}
        placeholder="Enter your name here"
      />
      <Button
        size="medium"
        primary={true}
        disabled={false}
        text="Click me!"
        onClick={() => alert("Button clicked!")}
      />
    </div>
  );
}

export default App;
```

## Contributing

This library is a demo for learning purposes only and is not intended to be contributed to. You can fork the repository and use the code for your personal use or learning.

## License

This demo UI library is licensed under the [MIT License](https://github.com/Timonwa/demo-ui-library/blob/main/license).