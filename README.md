## Hi, I'm Odhrán 👋

**Senior Full Stack Software Engineer & Technical Lead** · Vancouver, BC

I build and run backend systems where correctness matters, plus the web and mobile front ends on top of them. I'm currently Technical Lead at **UKG Shiftboard**, where my team builds the integration platform that moves schedule, timecard and clock-punch data into enterprise payroll systems.

[Portfolio](https://www.odhran.ca) · [LinkedIn](https://www.linkedin.com/in/odhrandaly) · odaly064@gmail.com

### What I work on

- **UKG Shiftboard (2022 – now):** a horizontally scaling .NET integration service. Concurrent per-customer jobs run over RabbitMQ with idempotent processing, Redis caching and tuned SQL, and I'm leading the migration of per-tenant run locking from Redis to Microsoft Orleans. I'm on the team's on-call rotation, and features I designed drove $130k in new ARR.
- **Guidewire (2019 – 2022):** Java and Spring Boot microservices for cloud customers. Cut customer update time from 3 months to 2 hours, and shipped the Log4j zero-day patch to 66 cloud environments in 72 hours.
- **AI-assisted development:** I use Claude Code every day, at work and on my own projects, and introduced agentic workflows into my team's development process.

### Featured project: Rec Pass Hub

A full-stack discovery and pass management platform I designed and built end to end. It runs in Docker on a Kubernetes cluster I built at home, with Stripe for payments.

| Repo | What it is | Stack |
|---|---|---|
| [recpasshub-service](https://github.com/dalyodhran/recpasshub-service) | Backend API for events, passes, waivers and users | Java · Spring Boot · PostgreSQL · Redis · Keycloak (OAuth2) |
| [recpasshub-app](https://github.com/dalyodhran/recpasshub-app) | Mobile app for attendees and organizers, with passes, QR check-in scanning, waivers and maps | React Native (Expo) · TypeScript |
| [recpasshub-ui](https://github.com/dalyodhran/recpasshub-ui) | Organizer web dashboard | React · TypeScript · Vite |
| [recchubpass-docker](https://github.com/dalyodhran/recchubpass-docker) | Supporting services: Keycloak, PostgreSQL, Redis cluster, Prometheus and Grafana | Docker Compose |

### Tech

- **Backend:** Java, Spring Boot, C# / .NET, Microsoft Orleans, REST APIs, microservices, event-driven design
- **Data and messaging:** PostgreSQL, SQL, Redis, RabbitMQ
- **Front end:** React, TypeScript, React Native, Angular
- **Cloud and ops:** AWS (Certified Developer – Associate), Azure, Docker, Kubernetes, Terraform, Prometheus, Grafana
- **Auth:** Keycloak, OAuth2 / OIDC, role-based access control

Outside of code, I run marathons.
