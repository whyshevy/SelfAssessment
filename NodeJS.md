## Node.js and backend

- Internals and concepts
  - Strong and weak sides of node.js: 👂 heard
  - Stateful and stateless servers:
  - Nonblocking I/O and slocking code :👂 heard
  - Event loop: phases:
  - Event loop: microtasks and macrotasks: 👂 heard
  - Garbage collection: 📢 talked
  - Node.js LTS schedule :👂 heard
  - I/O-bound, CPU-bound, memory-bound tasks:
  - Interactive applications (close to real-time):
- Modularity, layers and dependencies
  - CommonJS modules: 📢 talked
  - ECMAScript modules: 📢 talked
  - node:module :
  - Caching in CJS and ESM: 👂 heard
  - Modules as singletons: 📢 talked
  - Contexts and scripts node:vm:📢 talked 
  - Dependencies: npm, node_modules: 📢 talked 
  - Dependencies: package.json and package lock:
  - Module-based permissions model :👂 heard
  - Isolation with modularity:
  - Dependency injection:
  - DI containers: 👂 heard
  - Coupling and cohesion: 📢 talked
  - Framework agnostic approach:
- Environment
  - Command line arguments:
  - Node.js CLI:
  - Process-based permissions:
  - Graceful shutdown :👂 heard
  - Clustering: 📢 talked
  - Watch filesystem changes with --watch: 🚀 constructed
- Internal API
  - Streams API: 👂 heard
  - Web Streams API:  👂 heard
  - Crypto API:  👂 heard
  - Password hashing with node:crypto.scrypt:
  - Web Crypto API: 
  - File system API: sync and async:
  - Copy folder recursively:
  - Worker threads: 📢 talked
  - Performance hooks: 👂 heard
  - Native fetch and nodejs/undici:
  - node:async_hooks: 
  - AsyncLocalStorage:
  - AsyncResource: 👂 heard
  - Deprecated domain API:
  - Node.js single executable: 📢 talked
  - Stream back pressure:
  - SharedArrayBuffer:
  - node:worker_threads:
  - node:child_process:
  - MessageChannel, MessagePort:
  - BroadcastChannel: 👂 heard
  - Generating crypto random UUID:
  - node:url vs new URL: 📢 talked 
  - node:assert: 📢 talked
  - Internationalization: 📢 talked
  - Blob, File, Buffer, node:buffer: 📢 talked
  - Module node:zlib:
- Application structure and architecture
  - Isolation between layer:
  - Multilayer approach: 👂 heard
  - Separation of concerns:
  - Inversion of control: 👂 heard
  - Dependency injection: 👂 heard
  - GRASP: 📢 talked
  - SOLID: 📢 talked
  - GoF patterns: 📢 talked
  - Distributed systems: 📢 talked
  - Highload applications: 📢 talked
  - Clean architecture: 📢 talked
  - DDD: 👂 heard
  - Message Queue: 👂 heard
  - CQS:
  - CQRS: 👂 heard
  - Event sourcing:
  - Load balancing: 📢 talked
  - Serverless clouds: 📢 talked
  - FaaS clouds :👂 heard
  - Fat controller:
  - GoF for Node.js: 📢 talked
  - Leaking abstractions:
- Network
  - IP sticky sessions:
  - Endpoint throttling:
  - HTTP(S): 👂 heard
  - TCP/SSL: 👂 heard
  - UDP: 👂 heard
  - TLS: 👂 heard
  - Websocket: 👂 heard
  - SSE: 📢 talked
  - HTTP/3 (QUIC):
  - Long polling:
  - REST: 👂 heard
  - RPC: 📢 talked
  - Routing: 📢 talked
  - DoS: 📢 talked
  - DDoS: 👂 heard
  - XSS:
  - Path traversal:
  - CSRF:
  - DNS: 📢 talked
  - Fetch API: 📢 talked
  - IncomingMessage:
  - SQL injection: 📢 talked
  - noDelay:
  - keep-alive:
  - ALPN:
  - SNI callback:
  - SSL certificates: 👂 heard
  - Protocol agnostic approach: 📢 talked
- Technique and tools
  - Native test runner:
  - Logging: 📢 talked
  - Application configuring:
  - Testing:
  - CI/CD: 👂 heard
  - Readable: 📢 talked
  - Writable: 📢 talked
  - Transform:
  - back pressure:
  - Buffer: 📢 talked
  - Console: 📢 talked
  - Inspector:👂 heard
  - Reliability: 👂 heard 
  - Quality: 👂 heard
  - Availability: 👂 heard
  - Flexibility: 👂 heard
- Data access
  - Data access layer: 🚀 constructed
  - Repository:
  - Active record:
  - Query builder:  🚀 constructed
  - Object-Relational Mapping: 🚀 constructed
- Error handling and debugging
  - Error:
  - error.cause:
  - error.code:
  - error.message:
  - error.stack:
  - How to avoid mixins:
  - Error.captureStackTrace:
  - Uncaught exceptions: 
  - Heap dump:
  - Debugging tools:
  - Flame graph: 📢 talked
  - Memory leaks: 👂 heard
  - Resource leaks: 👂 heard
  - Data race: 📢 talked
- Integrations and bindings
  - Native addons: 👂 heard
  - C and C++ addons:
  - Rust addons: 
  - Zig addons:
  - NAN (Native Abstractions for Node.js):
  - Node-API (formerly N-API):
  - NAPI C and C++:
  - NAPI Rust:
  - NAPI Zig:
  - Webassembly WAT:
  - Webassembly C and C++:
  - Webassembly Rust:
  - Webassembly Zig:
  - Webassembly AssemblyScript:
  - Shared memory: 👂 heard
  - SharedArrayBuffer: 👂 heard
  - V8 binary serialization 👂 heard: