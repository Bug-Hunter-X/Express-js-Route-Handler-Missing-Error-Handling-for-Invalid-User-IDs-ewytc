# Express.js Route Handler Missing Error Handling for Invalid User IDs

This repository demonstrates a common error in Express.js route handlers: the lack of error handling when dealing with user input.  Specifically, this example shows a route that fetches a user by ID, but fails to handle cases where the ID is not a valid number. This can lead to unexpected behavior or crashes.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file demonstrates how to add robust error handling.