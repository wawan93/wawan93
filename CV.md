# Vladimir Kochergin
## Senior Backend Developer

Professional Backend engineer with 10+ years of experience in web development. Proven track record of high load projects using Golang and PHP. Proficient at implementing microservices architecture, code optimization for high load, set up CI/CD and cloud infrastructure.

## Contact information

* Email: github@wawan.pro
* Telegram: http://t.me/wawan2030
* Github: https://github.com/wawan93
* StackOverflow: https://stackoverflow.com/users/6130095

## Tech stack

- **Languages**: Golang, PHP, Node.js, Ruby
- **Tools**: ElasticSearch, MySQL, PostgreSQL, MongoDB, Kafka, NATS, gRPC, Laravel, Vue.js, Distributed Systems, WebSockets, MicroServices
- **Devops**: AWS, GCP, Kubernetes, Docker, Gitlab CI/CD, Github Actions
- **Logs**: ELK, OpenTracing, Jaeger, Grafana, Prometheus
- Russian (native), English (intermediate)

## WORK EXPERIENCE

### Senior Golang Developer. LookFirst.io, New York, remote (Mar 2022 - Present)
Social network with AI-generated images for streamers and Anime fans
- Moved golang-monolith into microservices, because of heavy video-processing with CPU
- Led process of migration from Node.js monolith to Golang + NATS microservice infra
- Made an internal workshop for a team of Node.js developers about Golang best practices
- Worked with Google Cloud functions, tasks, and lambda functions for video processing and notifications
- Designed and implemented notifications service from the ground up
**Stack:** Golang, PostgreSQL, NATS, MongoDB, Google Cloud functions, Docker, Kubernetes

### Lead Golang Developer. Astradot. San Francisco, remote (Jan 2020 - Feb 2022)
Worked in a USA startup, which mission was enabling to see paths of incoming requests through the whole infrastructure
- Created an advanced observability OpenTracing tool based on Jaeger's fork with paths ver 1.0
- Worked on Ingester that enables storing and querying data (volume - 5k traces per second)
- Collected data with Kafka and streamed logs into ElasticSearch and Grafana-Tempo storage
- Made real-time integration with Kubernetes (k8s) gathering logs, metrics, and health-checks
**Stack:** Golang, Kafka, Grafana Tempo, ElasticSearch, AWS, Kubernetes

### Tech Lead Golang Developer. Blockchain startup. Cyprus, remote (Jan 2019 - Dec 2019)
Started as a Senior Engineer, then grew up to Tech Lead for data blockchain integration
- Made mobile and web-based API for blockchain data (token prices, transactions, volumes)
- Built own blockchain scanner on top of Golang and NATS using ETL pipelines
- Made integrations with KYC/KYB system
**Stack:** Golang, PostgreSQL, NATS, Docker, Kubernetes

### Senior Golang/PHP Developer. SberMegaMarket. Moscow (Oct 2016 - Dec 2018)
Worked in the biggest retail marketplace with 20+mil MAU from the company’s foundation. During work, I have participated in 3 company’s key products

**Price Crawler**
- Developed crawlers and parsers for online retail merchants. Created parsers to get current prices and availability.
- Optimized code and queries for high load (~10k prices per minute)
- Provided cleaned data for the ML team via ETL pipelines
- **Stack:** Golang, NATS, MongoDB, Kafka, Docker, kubernetes

**Logistics service**
- Our goal was to register orders in delivery services and track their statuses
- Integration with third-party delivery services' APIs
- Refactored services to handle 5x more orders
- Make a telegram bot for monitoring incidents
- **Stack:** Golang, PostgreSQL

**Authorization microservice**
- Made user profile and auth service with JWT
- Developed chat dialog service, integrated with BPM and other services
- Developed system from scratch on Golang

### PHP Developer. Rambler. Moscow (Oct 2014 - Oct 2016)
Worked on quto.ru, high-load (3mil+ MAU) auto portal
- Moved site from PHP5 to 7
- Optimized main SQL queries for high load (add indexes, denormalisation data, master-slave DBS)
- Moved PHP distributed monolith to Ruby
- Key achievement: Optimized key parts of the system for high load

### Junior PHP developer. QuantumSoft. Tomsk (May 2013 - Sep 2014)
Worked in outsource development team with ERP system
- Refactored the old legacy code from procedural style to OOP
- Developed API and PHP SDK and WordPress plugin based on this SDK
- Optimized the architecture and database requests for large amounts of data.
- Wrote tests for essential parts of the system
