Java Profiler

It's a lightweight, custom Java bytecode-instrumentation profiler: an agent injects timing/counting code into class methods at load time via Javassist, exposes the collected stats over a TCP socket (JSON protocol via Jackson), and a separate Swing-style client UI connects to start/stop profiling and view live per-method invocation counts and execution times — demoed against a sample ATM application.
