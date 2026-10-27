<div align="center">

# 👨‍💻 Nikunj Garg
### **Java Backend Developer | BCA Student**
📍 Dehradun, India

[![Portfolio](https://img.shields.io/badge/Portfolio-nikunjgarg.xyz-000000?style=for-the-badge&logo=firefox&logoColor=white)](https://nikunjgarg.xyz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nikunj_Garg-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nikunj-garg-36045b37a/)
[![LeetCode](https://img.shields.io/badge/LeetCode-@Nikunjgarg12-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Nikunjgarg12/)
[![Email](https://img.shields.io/badge/Email-gargnikunj991@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gargnikunj991@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-gargnikunj991--ux-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gargnikunj991-ux)

<p align="center">
  <em>Engineering secure, resilient, high-concurrency backend architectures with Java 21, Spring Boot 3, PostgreSQL, and Redis.</em>
</p>

---

</div>

## 📌 Summary

BCA student with hands-on experience developing high-concurrency backend systems using **Java 21, Spring Boot 3, PostgreSQL, and Redis**.
- 🛠️ **Core Specialization:** Distributed locks (**Redisson**), ACID concurrency control, idempotency gates, stateless **JWT security (Refresh Token Rotation)**, and real-time **WebSocket (STOMP)** messaging.
- 🧪 **Testing & Resilience:** Backed by automated **JUnit 5 stress, multi-threaded concurrency, and failure-mode testing**.
- 🎯 **Career Goal:** Seeking a **Remote Backend Engineering Internship** in Java / Spring Boot.

---

## 🛠️ Technical Skills

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | `Java 21`, `SQL` |
| **Backend & Distributed** | `Spring Boot 3`, `Spring Data JPA`, `Hibernate ORM`, `RESTful APIs`, `WebSockets (STOMP)`, `Distributed Locks (Redisson)` |
| **Databases & Caching** | `PostgreSQL`, `Redis 7 (TTL Leases, Keyspace Events)`, `Schema Design (3NF)`, `ACID Transactions`, `Locking (Pessimistic/Optimistic)` |
| **Security & Testing** | `Spring Security`, `JWT (Refresh Token Rotation)`, `Role-Based Access Control (RBAC)`, `JUnit 5 (70 Tests)`, `Mockito` |
| **Tools & DevOps** | `Docker`, `Docker Compose`, `Git`, `GitHub`, `Maven`, `Postman`, `Micrometer`, `OpenAPI 3.0`, `Render` |

<br/>

<div align="center">

### Tech Stack

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis_7-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Maven](https://img.shields.io/badge/Apache_Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI_3.0-85EA2D?style=for-the-badge&logo=openapiinitiative&logoColor=black)

</div>

---

## 🚀 Featured Projects

### 🎟️ [TicketWave — Distributed Seat Hold & Checkout Engine](https://github.com/gargnikunj991-ux/TicketWave)
> **Tech Stack:** `Java 21` • `Spring Boot 3` • `Redis 7 (Redisson)` • `PostgreSQL` • `Micrometer` • `JUnit 5`

- **Distributed Locking:** Architected distributed seat hold allocation using **Redisson MultiLock** across Redis (`<1ms`) with deterministic seat-ID sorting to eliminate deadlocks under high-concurrency arena ticket spikes.
- **Idempotency Gate:** Built a **Redis `SETNX` idempotency gate** (`IN_PROGRESS 120s / COMPLETED 24h`) and decoupled payment execution outside DB boundaries, preventing HikariCP pool exhaustion with atomic PostgreSQL commits.
- **Dual-Tier Reclamation Pipeline:** Engineered a dual-tier inventory reclamation pipeline (**Redis keyspace pub/sub + scheduled PostgreSQL sweeper**) to auto-reclaim expired 10m holds.
- **Automated Stress Testing:** Verified zero overselling with **70 automated JUnit 5 tests**.

---

### 💬 [DevTinder — Developer Matching & Messaging Platform](https://github.com/gargnikunj991-ux/Devlynix-Buildathon-2.0)
> **Tech Stack:** `Java 21` • `Spring Boot 3` • `PostgreSQL` • `WebSockets (STOMP)` • `Spring Security` • `Docker`

- **Real-Time Messaging:** Built bidirectional real-time messaging using **Spring WebSocket (STOMP)** paired with REST delta synchronization (`?after={id}`) and PostgreSQL persistence so users can retrieve missed messages upon reconnecting.
- **Discovery & Ranking Engine:** Implemented a developer discovery and matching service that ranks candidate profiles dynamically by shared skill counts in descending order and tracks mutual interest using unique composite constraints on swipe records.
- **Hardened Security & RTR:** Hardened authentication using stateless Spring Security filters, short-lived JWT access tokens, sliding-window IP rate limiting, and **Refresh Token Rotation (RTR)** with token family tracking to detect and revoke compromised sessions.
- **Cloud-Ready Containerization:** Containerized the backend using a multi-stage Dockerfile and configured environment variables and health-check endpoints (`/api/health`) for cloud deployment integrating with a Next.js frontend. Engineered and deployed in 72 hours during Devlynix Buildathon 2.0.

---

### 📚 [LibroSphere — Library Management & Reservation System](https://github.com/gargnikunj991-ux/library_spring)
> **Tech Stack:** `Java 21` • `Spring Boot 3` • `PostgreSQL` • `Spring Data JPA` • `Spring Security` • `Docker` • `JUnit 5`

- **Pessimistic Row-Level Locking:** Implemented pessimistic row-level locking (`SELECT ... FOR UPDATE`) in Spring Data JPA within atomic `@Transactional` boundaries to prevent race conditions and inventory overselling during concurrent checkouts.
- **Concurrency & ACID Verification:** Verified thread safety and ACID resilience with an automated JUnit 5 integration test using `CountDownLatch` and `ExecutorService`, proving **10 concurrent threads competing for 1 copy produced exactly 1 loan and 9 rejections with zero underflow**.
- **Automated FIFO Waitlist:** Architected an automated FIFO reservation waitlist that intercepts returned books, holding them exclusively for queued patrons with a 48-hour pickup window before restoring unclaimed inventory to general circulation.
- **Scheduled Penalties & Query Indexing:** Built an automated nightly cron worker (`@Scheduled`) calculating tiered overdue penalties and added composite B-Tree indexes on `(returned, due_date)` and `(book_id, status, reserved_at)` to avoid full table scans.

---

## 📊 GitHub & Problem Solving Activity

<div align="center">

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://github-readme-stats.vercel.app/api?username=gargnikunj991-ux&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=61AFEF&icon_color=E06C75&text_color=ABB2BF" width="100%" alt="GitHub Stats" />
    </td>
    <td align="center" width="50%">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gargnikunj991-ux&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=61AFEF&text_color=ABB2BF" width="100%" alt="Top Languages" />
    </td>
  </tr>
  <tr>
    <td align="center" colspan="2">
      <img src="https://streak-stats.demolab.com?user=gargnikunj991-ux&theme=tokyonight&hide_border=true&background=0D1117&ring=61AFEF&fire=E06C75&currStreakLabel=61AFEF" width="85%" alt="Streak Stats" />
    </td>
  </tr>
  <tr>
    <td align="center" colspan="2">
      <a href="https://leetcode.com/u/Nikunjgarg12/">
        <img src="https://leetcard.jacoblin.cool/Nikunjgarg12?theme=dark&font=Ubuntu" width="65%" alt="LeetCode Stats" />
      </a>
    </td>
  </tr>
</table>

</div>

---

## 🎓 Education

**Bachelor of Computer Applications (BCA)**  
*Shri Guru Ram Rai University, Dehradun* | **2025 – 2028**  
- **Cumulative CGPA:** `7.48 / 10.0`
- **Semester 2 SGPA:** `7.96 / 10.0`

---

## 🏆 Leadership & Key Achievements

- **Secretary — TechMantra Coding Club:** Promoted from Core Member to Secretary within 10 months; organized 5+ hands-on coding bootcamps and technical workshops for **120+ student developers**.
- **Startup Innovation Recognition:** Awarded Certificate of Recognition from UCOST & SGRR University IIC for pitching the startup concept *College Clash* in university innovation competitions.
- **Smart India Hackathon (SIH'26 Internal Round):** Awarded Certificate of Participation, collaborating in a collegiate software team to architect solutions for national-level problem statements.
- **Hackathon Competitions:** Awarded Certificate of Participation in **Algothon'26 (Algoxilla)**; engineered and deployed DevTinder backend in 72 hours during Devlynix Buildathon 2.0.
- **Algorithmic Problem Solving:** Solved data structures and algorithms problems in Java on **[LeetCode (@Nikunjgarg12)](https://leetcode.com/u/Nikunjgarg12/)**, focusing on arrays, strings, two-pointers, and linked lists.

---

## 🤝 Let's Connect

I'm always open to discussing backend engineering, distributed systems, concurrency control, database design, or internship opportunities!

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-nikunjgarg.xyz-000000?style=for-the-badge&logo=firefox&logoColor=white)](https://nikunjgarg.xyz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nikunj_Garg-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nikunj-garg-36045b37a/)
[![LeetCode](https://img.shields.io/badge/LeetCode-@Nikunjgarg12-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Nikunjgarg12/)
[![Email](https://img.shields.io/badge/Email-gargnikunj991@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gargnikunj991@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-gargnikunj991--ux-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gargnikunj991-ux)

</div>
