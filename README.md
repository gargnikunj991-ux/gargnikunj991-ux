# Hi, I'm Nikunj Garg 👋
### Java Backend Developer | BCA Student
📍 Dehradun, India

[![Portfolio](https://img.shields.io/badge/Portfolio-nikunjgarg.xyz-black?style=flat-square&logo=firefox&logoColor=white)](https://nikunjgarg.xyz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nikunj_Garg-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nikunj-garg-36045b37a/)
[![Email](https://img.shields.io/badge/Email-gargnikunj991@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:gargnikunj991@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-gargnikunj991--ux-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/gargnikunj991-ux)

---

### 👨‍💻 About Me
BCA student at Shri Guru Ram Rai University (2025–2028) with hands-on experience engineering high-concurrency backend systems using **Java 21, Spring Boot 3, PostgreSQL, and Redis**.
- 🛠️ **Engineering Focus:** Distributed locks (Redisson), ACID concurrency control, idempotency gates, stateless JWT authentication (Refresh Token Rotation), and real-time WebSockets (STOMP).
- 🧪 **Testing:** Backed by automated multi-threaded stress and failure-mode testing using JUnit 5.
- 🎯 **Career Goal:** Seeking a **Remote Backend Engineering Internship** in Java / Spring Boot.

---

### 🛠️ Technical Stack
- **Languages:** Java 21, SQL
- **Backend & Distributed:** Spring Boot 3, Spring Data JPA, Hibernate ORM, RESTful APIs, WebSockets (STOMP), Distributed Locks (Redisson)
- **Databases & Caching:** PostgreSQL, Redis 7 (TTL Leases, Keyspace Events), Schema Design (3NF), ACID Transactions, Locking (Pessimistic/Optimistic)
- **Security & Testing:** Spring Security, Stateless JWT (Refresh Token Rotation), RBAC, JUnit 5, Mockito
- **Tools & DevOps:** Docker, Docker Compose, Git, GitHub, Maven, Postman, Micrometer, OpenAPI 3.0, Render

---

### 🚀 Projects

#### [TicketWave — Distributed Seat Hold & Checkout Engine](https://github.com/gargnikunj991-ux/TicketWave)
`Java 21` • `Spring Boot 3` • `Redis 7 (Redisson)` • `PostgreSQL` • `Micrometer` • `JUnit 5`
- Engineered distributed seat allocation using **Redisson MultiLock** across Redis (`<1ms`) with deterministic seat-ID sorting to eliminate deadlocks during concurrent spikes.
- Implemented a **Redis `SETNX` idempotency gate** (`IN_PROGRESS 120s / COMPLETED 24h`) and decoupled payment execution outside DB boundaries to prevent connection pool exhaustion.
- Built a dual-tier reclamation pipeline (**Redis keyspace pub/sub + scheduled PostgreSQL sweeper**) for expired holds; verified zero overselling with **70 automated JUnit 5 tests**.

#### [DevTinder — Developer Matching & Messaging Platform](https://github.com/gargnikunj991-ux/Devlynix-Buildathon-2.0)
`Java 21` • `Spring Boot 3` • `PostgreSQL` • `WebSockets (STOMP)` • `Spring Security` • `Docker`
- Built real-time messaging using **Spring WebSocket (STOMP)** with REST delta synchronization (`?after={id}`) and PostgreSQL persistence for reconnecting users.
- Implemented dynamic candidate discovery ranking profiles by shared skill counts and tracking mutual interest via composite constraints.
- Hardened security with stateless Spring Security filters, short-lived JWTs, sliding-window rate limiting, and **Refresh Token Rotation (RTR)**.
- Containerized via multi-stage Dockerfile; engineered and deployed in 72 hours during Devlynix Buildathon 2.0.

#### [LibroSphere — Library Management & Reservation System](https://github.com/gargnikunj991-ux/library_spring)
`Java 21` • `Spring Boot 3` • `PostgreSQL` • `Spring Data JPA` • `Spring Security` • `Docker` • `JUnit 5`
- Prevented checkout race conditions and inventory overselling using **pessimistic row-level locking** (`SELECT ... FOR UPDATE`) in Spring Data JPA within atomic `@Transactional` boundaries.
- Verified thread safety and ACID resilience with an automated integration test using `CountDownLatch` and `ExecutorService` (10 concurrent threads competing for 1 copy produced 1 loan, 9 rejections, zero underflow).
- Built an automated FIFO reservation waitlist intercepting returned books with a 48-hour pickup window, and scheduled nightly penalty calculation with composite B-Tree indexes.

---

### 🏆 Leadership & Achievements
- **Secretary — TechMantra Coding Club:** Promoted from Core Member to Secretary within 10 months; organized 5+ hands-on coding bootcamps and workshops for 120+ student developers.
- **Startup Innovation Recognition:** Awarded Certificate of Recognition from UCOST & SGRR University IIC for pitching the startup concept *College Clash*.
- **Smart India Hackathon (SIH'26 Internal Round):** Certificate of Participation, architecting solutions for national-level problem statements.
- **Hackathon Competitions:** Certificate of Participation in Algothon'26 (Algoxilla); built DevTinder backend in 72 hours during Devlynix Buildathon 2.0.

---

### 📬 Connect With Me
- **Email:** [gargnikunj991@gmail.com](mailto:gargnikunj991@gmail.com)
- **LinkedIn:** [linkedin.com/in/nikunj-garg-36045b37a](https://www.linkedin.com/in/nikunj-garg-36045b37a/)
- **Portfolio:** [nikunjgarg.xyz](https://nikunjgarg.xyz)
