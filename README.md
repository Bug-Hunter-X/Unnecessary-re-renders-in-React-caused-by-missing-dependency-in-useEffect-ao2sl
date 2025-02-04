# Unnecessary re-renders in React caused by missing dependency in useEffect
This repository demonstrates a common React bug: unnecessary re-renders caused by a missing dependency in the `useEffect` hook. 
The `useEffect` hook, when called without a dependency array, runs after every render. In this case, it leads to excessive logging to the console.
The solution shows how to fix this by correctly specifying the dependencies.