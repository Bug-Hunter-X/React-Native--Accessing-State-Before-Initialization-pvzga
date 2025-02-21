# React Native: Accessing State Before Initialization

This repository demonstrates a common error in React Native functional components: accessing state before it has been initialized. It also shows how to correctly handle this situation.

## Bug
The `bug.js` file shows the erroneous code, where the state variable `count` is accessed directly within the render function before the component has finished mounting. This results in `count` being undefined, leading to the error.

## Solution
The `bugSolution.js` file presents the corrected code.  It ensures the state variable `count` is only accessed after it's been properly initialized by using the conditional render or null check.