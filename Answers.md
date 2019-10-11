# Answers

1. What is React JS and what problems does it try and solve? Support your answer with concepts introduced in class and from your personal research on the web.

React JS is a coding language that combines HTML, CSS, and JavaScript by using JSX. It allows you to break an app and/or website down into smaller components. This is important, because as apps gain traction (a huge spike in the user base), it takes more memory to run properly. React allows you to conserve as much memory as possible by preventing leaks to give them a better user experience. You can also easily modify the "state" or current app's appearance/behavior based on the user's actions, such as clicking a like button.

1. What does it mean to think in react?

Thinking in React allows you to visualize how an app should be built before you begin the process. It's important to identify what asepcts of an app should be broken down into components. And you also need to figure out how and where props should be passed up or down through your file structure.

1. Describe state.

State is an object that figures out how a component should render based on the user's actions. It makes your app or website more dynamic and interactive while conserving as much memory as possible.

1. Describe props.

Props are basically attributes that you pass through components that determine their look and feel. For example, you could pass an image source through a prop tag to determine which image should render. Or you could pass header/paragraph styles through parameters to identify how they should look upon rendering.

1. What are side effects, and how do you sync effects in a React component to state or prop changes?

If a function attempts to modify something outside of its scope, then this is a side effect (more specifically a memory leak). Side effects can be prevented by surrounding the code in a useEffect hook. Putting an empty array at the end tells it to render once. Or specifying a specific array will cause it to only render on that individual element.
