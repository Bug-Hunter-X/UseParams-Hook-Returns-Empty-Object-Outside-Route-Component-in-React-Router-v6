# React Router v6 useParams Hook Issue

This repository demonstrates a common issue encountered when using the `useParams` hook in React Router v6.  The `useParams` hook must be used within a component rendered by a `<Route>` component. Using it outside this context will result in an empty object being returned, potentially causing errors and unexpected application behavior. 

The `bug.js` file shows the incorrect usage, while `bugSolution.js` demonstrates the corrected approach.