# Welcome to Shipworthy

Shipworthy is the home of **Journey**, an Elixir library for defining and running durable workflows.

Journey provides PostgreSQL-backed persistence, horizontal scalability across application replicas, orchestration, retries, crash recovery, scheduling, introspection and analytics.

Journey scales with your application. No cloud solutions to subscribe to or depend on. Nothing new to deploy and operate in your infrastructure, and your data stays with you, in your PostgreSQL database.

---

### Repos

* **[Journey](https://github.com/shipworthy/journey)** – an Elixir package for defining and running durable workflows. The package is published on https://hexdocs.pm/journey

* **[journey_horoscopes](https://github.com/shipworthy/journey_horoscopes)** – A LiveView "Hello World" example. A simple workflow that keeps a lot of UI state.
* **[jour_dash](https://github.com/shipworthy/jour_dash)** – A LiveView application built with Journey that simulates a food delivery service. A more complex workflow.


Repos used in the **[series on dev.to](https://dev.to/markmark/series/34410)** on building with Journey:
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
