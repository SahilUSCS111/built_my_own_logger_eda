# Node.js Logger Application

This is a simple Node.js application that logs memory usage and events to a file. The application uses the `fs` (File System) module to log events, the `os` module to retrieve system information (like memory usage), and the `events` module to create a custom event emitter.

## Features
- Logs memory usage statistics (free memory as a percentage of total memory) every 3 seconds.
- Logs custom messages to a file named `eventlog.txt`.
- Uses a custom `Logger` class that extends Node.js's `EventEmitter` to emit messages and log them.


