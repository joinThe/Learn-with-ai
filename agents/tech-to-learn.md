# Technologies to Learn — Roadmap

Context: Senior dev, strong in React/RN, working knowledge of Node/Python/SQL/Docker.
These fill gaps that matter for staff-level / full-stack credibility and system design conversations.

## Messaging & Event-Driven Systems
- **Kafka** — distributed event streaming, used for high-throughput pub/sub, event sourcing, decoupling services. Learn: topics/partitions, consumer groups, at-least-once vs exactly-once delivery.
- **RabbitMQ** — traditional message broker, simpler than Kafka. Learn: queues, exchanges, routing, when to pick this over Kafka (lower throughput, more flexible routing, task queues).
- **Redis** — in-memory store. Learn beyond basic caching: pub/sub, rate limiting, session storage, sorted sets for leaderboards, TTL strategies.

## Data & Storage
- **Elasticsearch** — full-text search, log aggregation (ELK stack). Common in systems needing search beyond SQL `LIKE`.
- **NoSQL (MongoDB or DynamoDB)** — understand when document/key-value stores beat relational, not just "SQL vs NoSQL" trivia.

## Infrastructure & Orchestration
- **Kubernetes** — you know Docker; K8s is the natural next step for orchestration, scaling, self-healing deployments. Even conceptual understanding (pods, services, deployments) is valuable for interviews and design discussions.
- **Nginx** — reverse proxy, load balancing, basic config. Useful even at a conceptual level.
- **CI/CD tools** (GitHub Actions, GitLab CI) — you likely need this anyway for your Weeks 5-6 stretch goal.

## Observability
- **Prometheus + Grafana** — metrics collection and dashboards. Pairs well with your monitoring stretch goal.
- **Structured logging** (e.g., Pino, Winston with log aggregation) — moves you from "console.log" thinking to production-grade observability.

## APIs & Communication
- **GraphQL** — alternative to REST, useful to know trade-offs (over-fetching/under-fetching, schema design) even if you don't adopt it.
- **gRPC** — for service-to-service communication, common in microservices interviews/discussions.
- **WebSockets** — real-time communication, likely relevant if any of your apps need live updates.

## System Design Fundamentals
- Load balancing strategies
- Caching strategies (cache-aside, write-through, invalidation)
- Database indexing & query optimization (SQL you know — go deeper on `EXPLAIN ANALYZE`)
- Horizontal vs vertical scaling, sharding basics
- CAP theorem — conceptual, comes up in senior-level discussions

## Suggested prioritization
1. **Redis** (quick win, immediately useful, low complexity)
2. **Kafka or RabbitMQ** (pick one — Kafka if you want the more "in-demand" skill, RabbitMQ if you want simpler/faster to learn)
3. **Kubernetes basics** (conceptual understanding first, hands-on later)
4. **Observability stack** (Prometheus/Grafana) — pairs directly with your existing project's stretch goal
5. Everything else — as-needed based on what comes up at work or in interviews

## Status
| Technology | Status | Notes |
|---|---|---|
| Redis | Not started | |
| Kafka/RabbitMQ | Not started | |
| Kubernetes | Not started | |
| Prometheus/Grafana | Not started | |
