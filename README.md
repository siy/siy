# Sergiy Yevtushenko

**Founder, Pragmatica Labs | Distributed Systems | Functional Java**

After 35 years building production systems - from embedded firmware to trading platforms - I founded Pragmatica Labs to solve the problems I kept seeing: fragile distributed architectures and unpredictable codebases.

The result is a unified stack: **Aether** (distributed runtime), **JBCT** (coding methodology + tooling), and **Pragmatica Lite** (functional primitives) - all working together to make Java backend development predictable and scalable.

## Pragmatica Labs

**Website:** [pragmaticalabs.io](https://pragmaticalabs.io)

We help teams build robust Java systems through technology and training. Our tools enforce correctness at compile time, and our methodology transforms "best practices" into mechanical rules that both humans and AI can follow.

## Featured Projects

### Aether
**Distributed Java Runtime** | [Repository](https://github.com/siy/aether) | [Watch Demo](https://www.awesomescreenshot.com/video/49014059?key=7c38f783c05577f9df19318ded22b966)

The third option between monolith and microservices. Write business logic as "slices," deploy distributed. Aether handles orchestration, scaling, and resilience.

- **Predictive autoscaling** - ML-based scaling that anticipates load, not reacts to it
- **Zero-downtime updates** - Two-stage deploy/route model with weighted traffic shifting
- **Chaos-tested** - 80 E2E tests covering node failures, network partitions, rolling restarts
- **Aether Forge** - Local simulator with visual dashboard for development

Business Source License 1.1 -> Apache 2.0 after 4 years.

### JBCT
**Java Backend Coding Technology** | [Repository](https://github.com/siy/coding-technology) | [Book](https://leanpub.com/jbct-book)

A methodology and tooling for writing deterministic, exception-free Java code. Designed for human-AI collaboration - when Claude or Copilot generates code, JBCT catches the mistakes.

- **Four return types** - `T`, `Option<T>`, `Result<T>`, `Promise<T>` cover all signatures
- **Six structural patterns** - Leaf, Sequencer, Fork-Join, Condition, Iteration, Aspects
- **CLI + Maven plugin** - Automated validation with zero false negatives
- **Parse, don't validate** - Invalid states become unrepresentable

### Pragmatica
**Unified Monorepo** | [Repository](https://github.com/pragmaticalabs/pragmatica)

All components in one place: core library, integrations, JBCT tooling, and Aether runtime.

| Module | Purpose |
|--------|---------|
| `core/` | Result, Option, Promise - functional primitives |
| `integrations/` | Jackson, Micrometer, JDBC, consensus |
| `jbct/` | CLI, Maven plugin, slice processor |
| `aether/` | Distributed runtime |

## Work With Us

- **Pilots** - Deploy Aether in your environment with direct support
- **Training** - JBCT workshops for your team
- **Consulting** - Architecture review and migration planning

## Get In Touch

- **Website:** [pragmaticalabs.io](https://pragmaticalabs.io)
- **Email:** sergiy.yevtushenko@pragmaticalabs.io
- **LinkedIn:** [sergiy-yevtushenko](https://www.linkedin.com/in/sergiy-yevtushenko-6977a12/)
