## Hi, I'm Raman Zanko! 👋

Senior software engineer with 9+ years of commercial experience building systems in fintech, banking, GIS, and enterprise software. I work in **Rust** and **C#**, with a focus on backend services, network programming, and data processing.

## Projects

### [semantic-gateway](https://github.com/roman-barman/semantic-gateway) — Semantic Layer / BI Gateway
Define business metrics and dimensions in YAML and query data through them over HTTP. Built on **Apache DataFusion**: semantic queries are translated into typed logical plans (no SQL string construction), with a pluggable data source abstraction and structured error handling.
`Rust` `DataFusion` `Actix-web` `Tokio` `Parquet`

### [blog-platform](https://github.com/roman-barman/blog-platform) — Multi-component blog system
Full-stack system in a single Cargo workspace: REST API (**Actix-web**), gRPC services (**Tonic**), **WebAssembly** frontend (Yew), CLI tooling, shared client library, PostgreSQL.
`Rust` `Actix-web` `Tonic` `Yew` `PostgreSQL`

### [bank-statement-parser](https://github.com/roman-barman/bank-statement-parser) — SWIFT & ISO 20022 statement tools
Library and CLI tools for real-world banking formats: **MT940** (SWIFT) and **CAMT.053** (ISO 20022). Parse, convert between formats, and reconcile transactions across files.
`Rust` `MT940` `CAMT.053` `Fintech`

### [quote-streamer](https://github.com/roman-barman/quote-streamer) — Real-time quote streaming service
Client-server system streaming stock quotes: subscription management over **TCP**, data delivery over **UDP**, multithreaded server with concurrent client handling.
`Rust` `TCP/UDP` `Multithreading`

### [image-processing-cli](https://github.com/roman-barman/image-processing-cli) — Plugin-based image processor
CLI with a **dynamically loaded plugin architecture**: filters compiled as shared libraries (`.so`/`.dll`) and loaded at runtime.
`Rust` `Dynamic loading` `CLI`

### Systems from scratch
Low-level implementations of real-world systems, built to understand how they work under the hood:
- [**Redis server**](https://github.com/roman-barman/codecrafters-redis-rust) — core commands, networking, data persistence
- [**DNS server**](https://github.com/roman-barman/codecrafters-dns-server-rust) — DNS protocol and query resolution
- [**Unix shell**](https://github.com/roman-barman/codecrafters-shell-rust) — command parsing, process management, built-ins

## Commercial Experience

- 9+ years of backend development (.NET/C#), currently adopting Rust for systems work
- Domains: fintech, banking, GIS, enterprise software
- Payment provider integrations, service migrations, architecture design, performance optimization
- Microservices, Clean Architecture, REST, gRPC, Kubernetes

## Reach me
- **Email:** [roman.zanko.vl@gmail.com](mailto:roman.zanko.vl@gmail.com)
- **LinkedIn:** [roman-zanko](https://www.linkedin.com/in/roman-zanko/)
