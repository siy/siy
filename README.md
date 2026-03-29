# Sergiy Yevtushenko

**Founder, Pragmatica Labs | Application Operating System for Java | 35 years production experience**

After 35 years building production systems -- from embedded firmware to trading platforms -- I founded Pragmatica Labs to solve the problems I kept seeing: fragile distributed architectures, unpredictable codebases, and operational complexity that grows faster than the applications it supports.

The result: **Aether** -- a fused application runtime that handles everything between your business logic and production. One binary, one config file, one system to operate. And **JBCT** -- a coding methodology that turns Java code into executable business process specifications.

## Pragmatica Labs

**Website:** [pragmaticalabs.io](https://pragmaticalabs.io)

## Aether

**Fused Application Runtime for Java** | [Repository](https://github.com/pragmaticalabs/pragmatica/tree/main/aether) | [Demo](https://www.awesomescreenshot.com/embed?id=50013933&shareKey=f16cf0ff602db9c4b7ff4928ecb382a7)

Write business logic as slices -- Java interfaces with methods. Deploy into a runtime that handles orchestration, scaling, resilience, streaming, security, and observability. No framework, no external infrastructure dependencies.

**What's built in:**
- Rabia consensus + two-layer topology (core + SWIM worker groups) -- proven at 12 nodes, zero failures
- QUIC transport for all inter-node communication -- first Java distributed runtime on QUIC
- HTTP/3 with dual-stack H1+H3 for application and management APIs
- In-memory streaming -- ordered, replayable, consumer-paced. No external message broker
- Cloud providers (AWS, GCP, Azure, Hetzner) -- raw REST APIs, no vendor SDKs
- Deployment strategies -- canary, blue-green, A/B testing with auto-rollback
- Schema migrations -- Flyway-style, consensus-coordinated, gated on readiness
- JWT/JWKS auth, RBAC (ADMIN/OPERATOR/VIEWER), operational audit trail
- Async PostgreSQL driver with built-in pipelining -- no external connection pooler
- Declarative cluster management -- bootstrap, scale, upgrade from a single TOML file
- Predictive autoscaling -- ML-based (ONNX) with 11-metric feature vector
- 500+ tests including 4-hour soak test with chaos injection

**Performance:** 8K req/s at sub-5ms p95 with real PostgreSQL on a laptop. Scales to 15K req/s.

Business Source License 1.1 → Apache 2.0 after 4 years.

## JBCT

**Java Backend Coding Technology** | [Repository](https://github.com/pragmaticalabs/pragmatica/tree/main/jbct) | [Documentation](https://pragmatica.dev) | [Book](https://leanpub.com/jbct-book)

A methodology and tooling for writing deterministic, AI-friendly Java code. Six structural patterns that map directly to BPMN constructs -- making code an executable business process specification.

- **Four return types** -- `T`, `Option<T>`, `Result<T>`, `Promise<T>` cover every method signature
- **Six patterns** -- Leaf, Sequencer, Fork-Join, Condition, Iteration, Aspects. Each maps to a BPMN construct.
- **BPMN bridge** -- code structure mirrors business processes. Readable by non-technical stakeholders.
- **CLI + Maven plugin** -- automated validation with zero false negatives
- **3.5% complexity ratio** -- measured by `scc`, compared to typical 12-18% in Spring Boot applications
- **Parse, don't validate** -- invalid states are unrepresentable

## Monorepo

**[pragmaticalabs/pragmatica](https://github.com/pragmaticalabs/pragmatica)** -- 230K lines of Java, 1,732 files

| Module | Purpose |
|--------|---------|
| `core/` | Result, Option, Promise -- functional primitives with zero dependencies |
| `integrations/` | Jackson, Micrometer, PostgreSQL, SMTP, cloud providers (AWS/GCP/Azure/Hetzner), XML, HLC |
| `jbct/` | CLI, Maven plugin, slice annotation processor |
| `aether/` | Distributed runtime, Forge simulator, Ember embeddable mode |

## Articles

- [We Should Write Java Code Differently: Let's Get Practical](https://dev.to/siy/we-should-write-java-code-differently-lets-get-practical-1ib2) (2026)
- [Nanoservices: Alternative to Monoliths and Microservices](https://dev.to/siy/nanoservices-or-alternative-to-monoliths-and-microservices-12bb) (2019)
- [We Should Write Java Code Differently](https://dev.to/siy/we-should-write-java-code-differently-210b) (2021)
- [Introduction to Pragmatic Functional Java](https://dev.to/siy/introduction-to-pragmatic-functional-java-142m) (2019)

## Get In Touch

- **Website:** [pragmaticalabs.io](https://pragmaticalabs.io)
- **LinkedIn:** [sergiy-yevtushenko](https://www.linkedin.com/in/sergiy-yevtushenko-6977a12/)
