# Hey, I'm Shehzad

**Senior Backend Engineer**

I'm a backend engineer who genuinely loves building things that work well under pressure. I run engineering at [RigRex](https://rigrex.com) where we build software for US and EU clients, and I also work as a full-time engineer at Uvicuo. Most of my code lives in private repos (client work), but I wanted this space to share a bit about who I am and how I think about problems.

## Background

I started out building Android apps: wallpaper apps, health apps that pulled sensor data from smartwatches, an IPTV app with BLE and local networking, and several others published to the Play Store. That hands-on mobile experience gave me a deep understanding of how clients actually consume APIs, which shapes how I design backends today.

Over time my curiosity pulled me toward the backend. I wanted to understand what happened on the other side of the network call. That turned into 7+ years of building production systems, and now backend engineering is what I do full time.

## What I Do Now

I run engineering operations at RigRex, where we build software for startups and growing companies. My day-to-day is a mix of architecture decisions, feature ownership, shipping code, mentoring engineers, and talking directly with clients.

On the backend side, I live in the Spring ecosystem with Kotlin and Java. I've worked across all three major clouds, built event-driven systems with message queues, managed complex workflows with state machines, and shipped microservices on Kubernetes and Docker. I care about the full lifecycle: designing it, building it, deploying it, monitoring it, and owning it when things go wrong at 2am.

Currently I own multiple core features at a product company. The kind of work where you're dealing with multi-instance state synchronization, workflow orchestration, event-driven reliability at scale, and keeping everything backward compatible while the product evolves fast underneath you.

## A Few Problems I've Enjoyed Solving

**Single instance to multi-instance (and everything that breaks).** A system that worked perfectly on one instance started having state inconsistency and syncing issues when we scaled out. Identified the root causes, redesigned the parts that assumed a single source of truth, and introduced event-driven patterns with message queues so instances could operate independently without stepping on each other.

**Scaling a platform 4x in 6 weeks.** A client was hitting limits at 500K monthly requests. Redesigned the architecture, set up proper monitoring and alerting, and got it to 2M/month without overcomplicating things.

**Replacing a server with a P2P network.** A POS system's server was choking under light load. Instead of throwing more resources at it, I moved task execution to a local device network with ledger-based syncing and automatic failover. Built the consistency and availability model from scratch. The server stopped being the bottleneck entirely.

**Monolith to microservices, no rewrite.** Introduced Hexagonal architecture into a growing monolith so features were already isolated by domain. When it was time to split services, the boundaries were clean and no big-bang rewrite was needed.

**Choosing where data gets processed.** On an IPTV project, moving file parsing from server to device cut infrastructure costs and made the system scale with users instead of against them.

## Why Private Repos

Client work under NDA. I'm planning to open-source a few utilities:

- [ ] Spring Boot + Hexagonal Architecture starter (Kotlin)
- [ ] Multi-instance state sync patterns for Spring Boot
- [ ] Spring State Machine workflow starter with error recovery and audit trails

## Get in Touch

**Email:** nazirshehzad1@gmail.com
**LinkedIn:** [shehzad-nazir-rigrex](https://www.linkedin.com/in/shehzad-nazir-rigrex)
**Company:** [rigrex.com](https://rigrex.com)
