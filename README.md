# Node.js Port Conflict Bug

This repository demonstrates a common error in Node.js where starting an HTTP server fails because the specified port is already in use.  The `bug.js` file contains the problematic code, and `bugSolution.js` provides a solution.

## Bug
The server attempts to bind to port 8080, but if another process (e.g., another server or a web browser) is already using this port, the server will fail to start.

## Solution
The solution involves checking if the port is available before attempting to bind to it or using a different port.
