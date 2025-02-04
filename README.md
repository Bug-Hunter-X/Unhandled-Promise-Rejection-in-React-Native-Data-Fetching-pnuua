# Unhandled Promise Rejection in React Native Data Fetching

This repository demonstrates a common issue in React Native applications: unhandled promise rejections during data fetching.  The `DataFetch.js` file shows a component that fetches data from an API.  However, it lacks comprehensive error handling, leading to potential crashes or unexpected behavior if the API request fails.

The solution, found in `DataFetchSolution.js`, demonstrates how to properly handle potential errors using a `try...catch` block and the `.then()` and `.catch()` methods. This ensures that any errors are caught and handled gracefully, preventing silent failures and improving app stability.

## How to reproduce

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run the application in your preferred React Native environment.
4. Observe the behavior of the `DataFetch` component.
5. Compare its behavior with the improved `DataFetchSolution` component.