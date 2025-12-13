# Welcome to Shipworthy ⚓️

**Reliable, distributed systems infrastructure for Elixir.**

Shipworthy is the home of **Journey**, a library that brings durable execution and resilient workflow orchestration natively to the BEAM. We build tools that help Elixir developers write complex, fault-tolerant business logic without managing external clusters.

---

### 🧭 The Ecosystem

#### 🚀 The Core
* **[Journey](https://github.com/shipworthy/journey)** – The main library. A native engine for defining and running durable workflows. If you are looking for the product, start here. The package is published on https://hexdocs.pm/journey

#### 💡 Reference Implementations and Demos
* **[jour_dash](https://github.com/shipworthy/jour_dash)** – A full-scale **Reference Application**. It simulates a food delivery service (complex state, multiple actors) to demonstrate how to model real-world business graphs.
* **[journey_horoscopes](https://github.com/shipworthy/journey_horoscopes)** – A lightweight "Hello World" example. Demonstrates how to connect Journey to a Phoenix LiveView front-end for reactive updates.

#### Blog Series

We are documenting the process of building with Durable Workflows and Journey in a **[series on dev.to](https://dev.to/markmark/series/34410)**. The following repos accompany these articles:

* **[journey_introspect](https://github.com/shipworthy/journey_introspect)** – Visualization and debugging tools for inspecting running workflows.
* **[useless_machine](https://github.com/shipworthy/useless_machine)** – A "useless" machine implementation. Just for fun, because engineers need hobbies too.

---

### 👨‍💻 About the Maintainer

Hi, I'm **Mark**. I am an **Engineer** based in Seattle, WA.

I started Shipworthy because I saw a gap in the Elixir ecosystem. I wanted the power of durable execution engines (like Temporal or Cadence) but without the operational overhead of running dedicated clusters or subscribing (and shipping data) to SaaS.

I built **Journey** to be the solution I wanted to use: a native Elixir package that handles the hard parts of distributed state—persistence, retries, and crash recovery—so you can focus on your business logic. Shipworthy currently uses this stack in production, providing Durable Workflow infrastructure to 

### 📜 Licensing

Shipworthy projects are **Source Available**.
* **Free** for non-commercial use and small businesses (revenue <$10k/month).
* **Commercial Licenses** available for larger production deployments.

[Visit gojourney.dev for full docs and details →](https://gojourney.dev)
