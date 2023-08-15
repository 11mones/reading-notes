# Lifting State Up in React

Lifting state up in a React application refers to the practice of moving the state from a lower-level component to a higher-level component
in the component tree. This approach is used to manage data flow more effectively and simplify the management of shared state and interactions
between components. By centralizing the state in a common ancestor component, you create a single source of truth for the data,
making it easier to control and modify the data from multiple child components.

**Benefits of lifting state up:**

* Single Source of Truth: When state is lifted up to a common ancestor, all components that need to access or modify that state do so through props. This ensures that all components are working with the same data and any updates are immediately reflected across the application.

* Data Consistency: Since the state is managed in one place, it reduces the chances of data inconsistency or out-of-sync states between components.

* Easier Debugging: With a clear flow of data, it becomes easier to trace the origin and flow of data changes, making debugging and troubleshooting more straightforward.

* Reusability: State lifted up to a higher-level component can be passed down as props to multiple child components, promoting component reusability and reducing duplication of state management logic.

* Simplified State Logic: Components become simpler as they are primarily concerned with rendering UI based on the props they receive, rather than managing complex state logic.

# Conditional Rendering in React

Conditional rendering in React involves rendering different content or components based on certain conditions or state values.
This allows you to dynamically display different parts of your UI depending on the data or user interactions.

**Example of conditional rendering:**


    import React, { useState } from 'react';

    function App() {
      const [isLoggedIn, setIsLoggedIn] = useState(false);

      return (
        <div>
          {isLoggedIn ? (
            <h1>Welcome, User!</h1>
          ) : (
            <button onClick={() => setIsLoggedIn(true)}>Log In</button>
          )}
        </div>
      );
    }

    export default App;
    
In this example, the isLoggedIn state determines whether to display a welcome message or a log-in button.
If the user is logged in, the welcome message is shown; otherwise, the log-in button is displayed.

# Principles of "Thinking in React"

* Break UI into a Component Hierarchy: Identify the various components that make up your UI and organize them hierarchically,
  representing parent-child relationships.

* Build a Static Version: Create a static version of your UI without interactivity or state. Focus on getting the structure and layout right.

* Identify the Minimal (but complete) Representation of State: Determine the minimal set of state that your app needs.
  This involves figuring out what data needs to be stored in the state and which components should manage it.

* Determine the Flow of Data: Understand how data flows through your components. Decide which components should hold the state,
  and how that state should be passed down as props.

* Add Interactivity: Add interactivity by implementing event handlers and state changes. Ensure that these changes flow through your
  component hierarchy as intended.

By following these principles, you approach the design and building process of a React application in a systematic and structured way,
leading to more maintainable, efficient, and well-organized code.
