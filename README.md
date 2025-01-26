# React Router v6 Catch-all Route Conflict

This repository demonstrates a common issue in React Router v6: conflicts with catch-all routes (`/*`).  The catch-all route unintentionally overrides other, more specific routes, even when those routes should be matched first. This can lead to unexpected routing behavior, where the catch-all route is used instead of the intended route.

The `App.js` file shows the problematic code.  The solution, in `AppSolution.js`, demonstrates how to correctly handle catch-all routes to prevent such conflicts.