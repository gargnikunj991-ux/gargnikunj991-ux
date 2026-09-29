
    I am a **BCA student** specializing in **Java backend development with Spring Boot 3, PostgreSQL, and Spring Security**.

    Experienced in architecting secure RESTful APIs, handling concurrency with row-level pessimistic locking, real-time WebSocket communication, relational database
  schemas, and deploying cloud backends across competitive hackathons and production-style projects.

    * 🔭 **Currently Building:** High-concurrency transaction backends and distributed lending engines.
    * ⚡ **Engineering Focus:** Clean Layered Architecture, Concurrency (`SELECT ... FOR UPDATE`), Database Transactions (ACID), and Unit Testing (JUnit 5).
    * 🎯 **Career Goal:** Seeking a **Remote Backend Engineering Internship** (Java / Spring Boot).

    ---

    # 🛠 Tech Stack

    | Domain | Technologies |
    | :--- | :--- |
    | **Languages & Database** | `Java 21` `SQL` `PostgreSQL` |
    | **Backend Frameworks** | `Spring Boot 3` `Spring Security` `Spring Data JPA` `Hibernate` `RESTful APIs` `WebSockets (STOMP)` |
    | **Security & API Standards** | `JWT (Access & Refresh Rotation)` `BCrypt` `Jakarta Validation` `OpenAPI / Swagger 3.0` |
    | **DevOps & Cloud** | `Docker` `Docker Compose` `Railway` `Cloudinary` `Git` `GitHub` `Maven` |
    | **Core Engineering** | `OOP` `Data Structures & Algorithms` `Relational Schema Design` `Clean Architecture` `JUnit 5 / Mockito` |

    ---

    # 🚀 Featured Projects

    ### 🌾 1. AgriSathi AI — Agricultural Intelligence & Decision-Support Platform
    > *Modular Java/Spring Boot backend for an AI-powered agricultural advisory platform developed during a 30-day hackathon.*

    * **Role-Based Security:** Architected secure **JWT authentication with RBAC** supporting `FARMER` and `BUYER` roles.
    * **Core Endpoints:** Built RESTful APIs for Farmer Profiles, Crop Lifecycle Tracking, and AI Disease Diagnosis (`POST /api/v1/disease/scan`) integrating computer
  vision and Cloudinary media pipelines.
    * **Integrations:** Integrated 7-day predictive hyper-local weather APIs and documented all endpoints with interactive **OpenAPI/Swagger 3.0**.
    * **Tech:** `Java 21` • `Spring Boot 3` • `Spring Security` • `PostgreSQL` • `Spring Data JPA` • `Cloudinary` • `Swagger`

    🔗 **[Live Demo](https://agri-sathi-ai-three.vercel.app/)** • 💻 **[GitHub Repository](https://github.com/gargnikunj991-ux/AgriSathi_AI.git)**

    ---

    ### 📚 2. LibroSphere — High-Concurrency Asset Lending & Reservation Engine
    > *High-throughput asset lending and reservation backend engineered to eliminate race conditions under concurrent load.*

    * **Pessimistic Row-Level Locking:** Eliminated double-checkout TOCTOU race conditions on multi-copy inventory using `@Lock(LockModeType.PESSIMISTIC_WRITE)` (`SELECT ...
  FOR UPDATE`) and atomic inventory decrements.
    * **FIFO Waitlist Queue:** Built an automated FIFO waitlist that intercepts returned assets, reserving 48-hour pickup windows for next-in-line patrons before public
  release.
    * **Security & Token Rotation:** Architected stateless JWT authentication with database-backed **Refresh Token Rotation** (`/auth/refresh`), role-based authorization,
  and centralized `@ControllerAdvice` error handling.
    * **Automated Testing Suite:** Built a **48-test automated suite (100% pass)** including a 10-thread concurrent stress test (`CountDownLatch`, `ExecutorService`)
  proving zero inventory underflow under contention.
    * **Tech:** `Java 21` • `Spring Boot 3` • `Spring Security` • `PostgreSQL` • `Hibernate` • `JUnit 5` • `Maven`

    💻 **[GitHub Repository](https://github.com/gargnikunj991-ux/library_spring.git)**

    ---

    ### 💻 3. DevTinder — Developer Teammate Matchmaking Platform
    > *Real-time matchmaking backend engineered and deployed in 72 hours during Devlynix Buildathon 2.0.*

    * **Relational API Layer:** Designed a PostgreSQL-backed relational API layer for developer profiles, tech stack tags, and mutual connection matching requests.
    * **Real-Time Communication:** Implemented bidirectional group and direct messaging using **WebSockets (STOMP protocol)** with persistent chat history.
    * **Production Deployment:** Configured production backend deployment on **Railway** with containerized environment variables and health check monitors.
    * **Tech:** `Java` • `Spring Boot` • `PostgreSQL` • `WebSockets (STOMP)` • `Railway`

    🔗 **[Live Demo](https://devlynix-frontend12-git-main-hxmblevishus-projects.vercel.app/)** • 💻 **[GitHub Repository](https://github.com/gargnikunj991-ux/Devlynix-
  Buildathon-2.0.git)**

    ---

    # 🎓 Education

    **Bachelor of Computer Applications (BCA)**
    *Shri Guru Ram Rai University, Dehradun (2025 – 2028)*
    * **Cumulative CGPA:** 7.48 / 10.0
    * **Semester 2:** 7.96 / 10.0

    ---

    # 🏆 Achievements & Leadership

    * 🎖️ **Secretary — TechMantra Coding Club:** Promoted from Member (10 months) to Secretary; coordinate technical student workshops and supported internal rounds for
  **Smart India Hackathon (SIH)**.
    * 💡 **Startup Innovation Recognition:** Awarded Certificate of Recognition for presenting an innovative startup idea at the **Innovation & Incubation Centre (IIC)**,
  SGRR University & UCOST.
    * 📜 **Java Programming Certification:** Certified in Java Programming through the **IIT Bombay Spoken Tutorial Project**.

    ---

    # 📈 Current Roadmap

    ```text
    Java 21 & Concurrency
       ↓
    Spring Boot 3 & Security (JWT Rotation)
       ↓
    Pessimistic Locking & ACID Transactions
       ↓
    Docker & CI/CD Pipelines
       ↓
    Production Engineering & Scale
  ──────Let's build scalable systems together!
    gargnikunj991@gmail.com • https://www.linkedin.com/in/nikunj-garg-36045b37a/ • nikunjgarg.xyz
