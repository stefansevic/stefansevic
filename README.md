# Hello, I'm Stefan!

### **CompTIA Security+ Certified | Software & IT Student at FTN Novi Sad**

I am a final-year student at the Faculty of Technical Sciences in Novi Sad, fully committed to a career in **cybersecurity** with a primary interest in **Security Operations (SOC)** and defensive security. While my academic background is in software engineering, I have dedicated my professional focus to threat detection, anomaly analysis, and protecting digital environments.

---

## Certifications
* **CompTIA Security+ ce**
    * **Candidate ID:** COMP001022976752
    * **Verification:** [Verify via Credly Digital Badge](https://www.credly.com/badges/87435066-4eb5-4841-9cd2-1b7cda290e86/public_url)

---

## Featured Projects

### [Network Traffic Analysis: Incident Report](https://github.com/stefansevic/Network-Traffic-Analysis-Incident-Report)
* Performed deep-packet analysis using **Wireshark** to identify and reconstruct a **Brute-Force attack** targeting HTTP Basic Authentication.
* Extracted compromised credentials from plaintext traffic and ensured forensic evidence integrity through **SHA-256 cryptographic hashing**.
* Authored a comprehensive **Incident Report** detailing the attack lifecycle and proposing strategic mitigations like **TLS/HTTPS implementation** and **Rate Limiting**.

### [Secure Distributed Music Streaming Platform]([https://github.com/annazecevic/spotify](https://github.com/stefansevic/distributed-music-platform))
- Designed end-to-end defensive architecture for a Go/Gin microservices system behind an **Nginx reverse proxy** (single public entry point).
- **AuthN/AuthZ:** enforced **HTTPS-only (TLS 1.2/1.3 + HSTS)**, **JWT authentication**, and mandatory **RBAC** middleware across services.
- **Availability & Input Security:** implemented multi-layer **rate limiting** (Nginx + app) and strict server-side **validation + sanitization/output encoding** aligned with **OWASP Top 10**.
- **Security Auditing (SAST):** ran **SonarQube** scans per service and produced a remediation plan (reduce complexity, remove duplicated literals, add tests/coverage targets).

 
### [Location & Event Management System](https://github.com/stefansevic/New-Now)
* Developed a full-stack decision-support platform using **Spring Boot 3.3** and **Angular 20**, implementing **JWT-based authentication** and **Role-Based Access Control (RBAC)**.
* Engineered secure administrative workflows for manual account approval and file uploads, emphasizing logic integrity and backend validation.
* Integrated **Spring Security** and **JPA** to ensure data persistence and protect REST endpoints, following secure development lifecycles for the SVT/KVA curriculum.

### [Configuration Management API](https://github.com/arsicc05/ars)
* Developed a lightweight REST API in **Go** for centralized configuration management and label-based filtering.
* Implemented a **security-oriented Rate Limiter** using the token-bucket algorithm to mitigate resource abuse and ensure system availability.
* Utilized **Docker** containerization to isolate the API environment, reducing the host's attack surface and simplifying secure infrastructure management.

### [Event Management System: Rust Microservices](https://github.com/stefansevic/event-management-rust)
* Designed and implemented a production-style **microservices architecture** using **Rust (Axum, Tokio, SQLx)** and a dedicated **Python (Flask) QR service**, orchestrated behind a centralized **API Gateway**.
* Built secure authentication and authorization flows with **JWT-based sessions** and **Role-Based Access Control (RBAC)**, enforcing strict separation between user and admin operations.
* Implemented event lifecycle management with **capacity validation, ticket generation, and QR code issuance**, including inter-service communication via internal Docker networking.
* Containerized the full stack using **Docker & Docker Compose**, provisioning isolated **PostgreSQL databases per service** to ensure clear bounded contexts and data separation.
---

## Technical Skills & Tools

| Category | Skills / Tools |
| :--- | :--- |
| **Cybersecurity** | Threat Detection, Log Analysis, Network Defense, OWASP Principles |
| **Tools** | Wireshark, Docker, Linux (CLI), VS Code, SonarQube |
| **Programming** | Java, C#, Python, Go, SQL, Rust |

---

## Education
* **Faculty of Technical Sciences (FTN), Novi Sad**
    * **Field:** Applied Software and Information Technologies
    * **Status:** Final-year student (2023 – Present)

---

### Connect with me
* **Location**: Novi Sad, Serbia
* **LinkedIn**: [Stefan Šević](https://www.linkedin.com/in/stefan-%C5%A1evi%C4%87/)
* **Email**: [seva002.ns@gmail.com](mailto:seva002.ns@gmail.com)
* **Phone**: +381 65 2143027

---
