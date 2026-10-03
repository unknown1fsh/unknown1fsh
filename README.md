<p align="center">
  <img src="./assets/the-one-header.svg" width="100%" alt="The One — Clean Code Advocate, Java and Spring full stack engineering" />
</p>

<p align="center"><b>Senior Full Stack Java Developer · Spring Ecosystem · Clean Code Advocate</b></p>

<p align="center">
  <a href="https://github.com/unknown1fsh?tab=repositories">Repositories</a> ·
  <a href="https://github.com/unknown1fsh?tab=overview">GitHub activity</a> ·
  <a href="https://www.linkedin.com/in/ssercanc/">LinkedIn</a>
</p>

## Engineering identity

Building enterprise applications with Java and Spring, web interfaces with Angular, and cross-platform mobile experiences with React Native. Focused on maintainable code, clear service boundaries, database performance, and visible business workflows.

<p align="center"><img src="./assets/clean-code.svg" width="100%" alt="Clean Code Advocate: meaningful names, focused functions, SOLID, testability and explicit dependencies" /></p>

**Clean Code Advocate** is the guiding principle: code should explain its intent, make failures understandable, and remain affordable to change.

## Core stack

<p align="center"><img src="./assets/tech-stack.svg" width="100%" alt="Backend: Java, Spring, Hibernate. Frontend: Angular and React Native. Data, workflow and development tooling." /></p>

<details>
<summary><b>Engineering practices</b></summary>

- REST API design, validation and centralized exception handling.
- Spring Security, transaction boundaries and JPA persistence.
- DTO mapping with MapStruct and dynamic queries with Specifications.
- SQL optimization, index design and deliberate ORM usage.
- Component architecture and responsive web interfaces.
- Camunda workflow automation and JasperReports reporting.

</details>

## Distributed systems / streaming at scale

A conceptual architecture study inspired by Netflix-scale engineering challenges. It illustrates a separation between API traffic and media delivery; it is not Netflix's official architecture or a claim of employment.

<p align="center"><img src="./assets/distributed-architecture.svg" width="100%" alt="Conceptual streaming architecture: clients use API and domain services for control, a CDN for media delivery, with media processing, service-owned data, events and cross-cutting observability." /></p>

**Design concerns:** bounded timeouts, selective retries with backoff, idempotency, fault isolation, graceful degradation, independent scaling and end-to-end observability.

## Camunda BPM / orchestration

Domain logic belongs in services. Process flow, waiting states and human approvals remain visible in the orchestrator.

<p align="center"><img src="./assets/camunda-orchestration.svg" width="100%" alt="Illustrative Camunda workflow: start, validate, decision, human or automatic approval, completion and technical recovery." /></p>

| Concern | Responsibility |
| --- | --- |
| Business rules and persistence | Java domain services |
| Process sequence and waiting state | Camunda orchestration |
| Human approval and deadlines | User tasks and timer events |
| Transient technical failures | Configured job or worker retries; incidents after exhaustion |
| Business rejection | Explicit process outcome or modeled business error |
| Undoing completed business work | Explicit compensation handlers, where required |

## Transmission

> I see everything, Carl. And in the end, you'll be the one working for me.

<p align="center">
  <a href="https://www.youtube.com/watch?v=alMMyxtJ2fA">
    <img src="./assets/video-cover.svg" width="100%" alt="Watch the original video on YouTube" />
  </a>
</p>

## Engineering doctrine

| Boundary | Purpose |
| --- | --- |
| Controller | Transport, request validation and API contracts |
| Service | Business rules, use cases and transactions |
| Repository | Persistence and data access |

Small responsibilities. Meaningful names. Explicit dependencies. Patterns that earn their place. Tests that verify behavior.

## Activity & connection

[Contribution history](https://github.com/unknown1fsh) · [Explore repositories](https://github.com/unknown1fsh?tab=repositories) · [LinkedIn](https://www.linkedin.com/in/ssercanc/)

<p align="center"><img src="./assets/footer.svg" width="100%" alt="Readable code. Visible flow. Resilient systems." /></p>
