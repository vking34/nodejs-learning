# NodeJS

Node.js is an open source, cross-platform runtime environment

## Characteristics
- Single Threaded:
     - Single thread runs through a queue of events

- Event Loop

- Asynchronous

- App.js is executed on the Runtime (could be implemented by C or C++) that can be multi-threading. But the App.js is potentially single-threaded.


## Good sides
- Non-blocking
- Event-driven
- Data-intensive
- I/O intensive

## Down sides
- Data calculations
- Compute-intensive
- Blocking operations

## Examples
- Web servers
- Realtime servers (the huge number of socket connections):
     - Less resource waste to keep connections.
- APIs fronting NoSQL DB:
     - You do not have a schema/ you have a flexible object model. Javascript is good at dealing with these flexible objects.
- Command line utilities
