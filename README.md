# Sergiy Yevtushenko

**Senior Software Architect | Java & Rust | Distributed Systems | Functional Programming**

I build robust, high-performance systems with a focus on type safety and eliminating entire categories of bugs at compile time. My work spans from low-level systems programming to distributed consensus protocols and developer tooling.

## What I Do

I specialize in designing systems where incorrect states are unrepresentable. This means leveraging advanced type systems, functional programming patterns, and careful API design to catch errors before they reach production.

My current interests include:
- Functional programming patterns for real-world backend systems
- Distributed consensus and fault-tolerant architectures
- AI-assisted development tooling and multi-agent coordination
- Hardware wallet security and blockchain infrastructure

## Featured Projects

### Pragmatica Lite
**Modern Functional Programming for Java 25** | [Repository](https://github.com/siy/pragmatica-lite)

Zero-dependency library providing monadic types (`Result<T>`, `Option<T>`, `Promise<T>`) that eliminate null pointer exceptions, unchecked exceptions, and callback hell. Built on sealed interfaces and pattern matching to fully leverage modern Java.

- Functional style error handling with type-safe exception management
- Async composition without callbacks or blocking
- Production-ready with Jackson, JPA, and Micrometer integrations
- Published on Maven Central

### Rabia-rs
**Rust Implementation of Rabia Consensus Protocol** | [Repository](https://github.com/rabia-rs/rabia)

A leaderless consensus protocol for building fault-tolerant distributed applications. Developers implement a simple `StateMachine` trait and the protocol handles all coordination across replicas.

- No leader election, no single point of failure
- Transparent node membership changes
- Memory pooling and zero-allocation hot paths
- Comprehensive fault injection testing

### Vibe Ensemble MCP
**Multi-Agent Coordination for Claude Code** | [Repository](https://github.com/siy/vibe-ensemble-mcp)

MCP server that enables Claude Code to manage specialized AI workers for complex development tasks. Implements stage-based pipelines with automatic worker spawning, dependency management, and quality gates.

- Real-time web dashboard for project monitoring
- Customizable worker templates
- Persistent state with pause-and-resume capability
- REST API and MCP tool integration

### Java Backend Coding Technology
**Framework-Agnostic Methodology for Predictable Java Code** | [Repository](https://github.com/siy/coding-technology)

A complete methodology transforming backend development from subjective "best practices" into an engineered technology with mechanical rules. Designed for human-AI collaboration with deterministic, testable code patterns.

- Four return types covering all function signatures (`T`, `Option<T>`, `Result<T>`, `Promise<T>`)
- Six structural patterns (Leaf, Sequencer, Fork-Join, Condition, Iteration, Aspects)
- Parse-don't-validate approach making invalid states unrepresentable
- Comprehensive guide with nine-part learning series

## Languages & Technologies

**Primary:** Java (17-25), Rust

**Areas:** Distributed Systems, Consensus Protocols, Functional Programming, API Design, Hardware Security (Ledger), Blockchain Infrastructure

## Get In Touch

- Email: Sergiy.Yevtushenko@gmail.com
- LinkedIn: [sergiy-yevtushenko](https://www.linkedin.com/in/sergiy-yevtushenko-6977a12/)

I'm always interested in discussing distributed systems, programming language design, and ways to make software more reliable through better abstractions.
