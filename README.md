# Node.js Express Server Delay Issue

This repository demonstrates a common issue in Node.js Express servers where the initial response is delayed due to asynchronous operations within the request handler.

The `server.js` file contains the buggy code.  The server takes 5 seconds to respond to the root path.  This is because of the `setTimeout` function within the request handler.

The `serverSolution.js` file provides a solution to mitigate this issue. 