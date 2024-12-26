# Intermittent Expo CLI Server Crashes

This repository demonstrates a bug where the Expo CLI development server intermittently crashes without providing any error messages in the console. The crash is unpredictable and occurs during development, often after making small code changes.  The application becomes unresponsive, requiring a manual restart of the Expo CLI server.  The issue is challenging to debug due to the lack of error indicators.

## Reproduction

The `expoBug.js` file contains a simplified example showcasing the problem. While this example may not always reproduce the bug, it highlights the scenario where the crash occurs.  The solution is found in `expoBugSolution.js`.

## Solution

The solution involves [insert explanation of solution e.g., carefully checking for memory leaks or using a more robust state management library or adding more detailed logging] which is demonstrated in `expoBugSolution.js`.