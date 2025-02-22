# React Native: TypeError: Cannot read properties of null (reading 'someProperty')

This repository demonstrates a common yet often overlooked error in React Native applications: the `TypeError: Cannot read properties of null (reading 'someProperty')`.  This error arises when attempting to access a property of an object that is currently `null` or `undefined`. This is particularly prevalent when working with asynchronous data fetching or optional chaining.

The `bug.js` file showcases the problematic code, while `bugSolution.js` provides a robust solution using optional chaining and nullish coalescing to gracefully handle these scenarios.

## How to reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` (or `yarn install`).
4. Observe the error in the `bug.js` example.
5. Refer to `bugSolution.js` for a correct implementation.