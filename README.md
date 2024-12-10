# Node.js Server Unresponsiveness Bug

This repository demonstrates a common issue in Node.js where a long-running task in a request handler can block the event loop, making the server unresponsive to other requests. The `bug.js` file contains the problematic code, while `bugSolution.js` provides a solution using asynchronous operations.