# React useEffect Hook: Missing Dependency
This repository demonstrates a common error in React's `useEffect` hook: omitting dependencies, leading to unexpected behavior and potentially infinite loops. 

The `bug.js` file shows the buggy code, where the `useEffect` hook lacks the `count` variable in its dependency array.  The `bugSolution.js` shows how to fix it by including the dependency.