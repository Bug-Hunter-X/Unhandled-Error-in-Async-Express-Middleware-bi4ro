# Unhandled Error in Async Express Middleware
This repository demonstrates a common error in Express.js applications: unhandled errors within asynchronous middleware.  The `bug.js` file showcases the issue, where an error thrown within a `setTimeout` callback isn't caught, causing the server to crash silently.

The `bugSolution.js` file provides a solution by implementing proper error handling using a `try...catch` block to gracefully handle the error and send an appropriate response to the client.