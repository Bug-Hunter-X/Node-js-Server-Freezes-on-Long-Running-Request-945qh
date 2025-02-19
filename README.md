# Node.js Server Freeze Bug

This repository demonstrates a common issue in Node.js applications: server freezes when a long-running synchronous operation is performed within the request handler.  The provided `server.js` showcases the problem.  The solution, `serverSolution.js`, demonstrates how to address the issue using asynchronous programming.