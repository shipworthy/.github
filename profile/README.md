Shipworthy is the home of **Journey**, an Elixir package for defining and running durable workflows.

Journey provides PostgreSQL-backed persistence, horizontal scalability across application replicas, orchestration, retries, crash recovery, scheduling, introspection and analytics.

Journey scales with your application. No cloud solutions to subscribe to or depend on. Nothing new to deploy and operate in your infrastructure, and your data stays with you, in your PostgreSQL database.

---

### Repos

* **[Journey](https://github.com/shipworthy/journey)** – an Elixir package for defining and running durable workflows. The package is published on [hexdocs.pm/journey](https://hexdocs.pm/journey)

* **[journey_horoscopes](https://github.com/shipworthy/journey_horoscopes)** – A LiveView "Hello World" example. A simple workflow that manages state and logic behind the application's user experience. Running on [horoscopes.gojourney.dev](https://horoscopes.gojourney.dev).
* **[jour_dash](https://github.com/shipworthy/jour_dash)** – A LiveView application built with Journey that simulates a food delivery service. A more complex workflow. Running on [jourdash.gojourney.dev](https://jourdash.gojourney.dev).

Repos used in the **[dev.to series](https://dev.to/markmark/series/34410)** on building with Journey:
* **[journey_introspect](https://github.com/shipworthy/journey_introspect)** – An example of introspecting a running workflow for "[The Mystery of a Missing Greeting](https://dev.to/markmark/the-mystery-of-a-missing-greeting-3ebf)."
* **[useless_machine](https://github.com/shipworthy/useless_machine)** – A Useless Machine implementation for "[Building a Useless Machine in Elixir](https://dev.to/markmark/building-a-useless-machine-in-elixir-42i1)."

---

### About the Maintainer

Hi, I'm Mark. I am an engineer here in Seattle, WA.

Journey exists because I wanted the power of durable execution engines (like Temporal or Cadence) but without the operational overhead of running dedicated clusters or subscribing (and shipping data) to "the cloud."

Which is what I built Journey to be: an Elixir package that handles the hard parts of distributed state – PostgreSQL-based persistence, retries, and crash recovery – so you can focus on your business logic.

We use Journey in production applications.

---

### Licensing

Journey is **Source Available**.
* **Free** for non-commercial use and small businesses (revenue <$10k/month).
* **Commercial Build Keys** are available for other projects.

Journey Demos use the MIT License.

Visit [gojourney.dev](https://gojourney.dev) for full docs and details.

---
Built with 💙💛 in Seattle, WA.
