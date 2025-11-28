# InterviewAI Backend

This is the backend service for InterviewAI — a platform that conducts mock interviews, evaluates candidate responses, and provides AI-generated analysis.

## 🚀 Features
- Candidate registration & onboarding
- Recruiter assignment creation
- Question delivery & answer submission
- Audio-to-text processing (via external integration)
- AI evaluation endpoint
- PostgreSQL database integration
- REST API using Spring Boot

---

## 🛠 Tech Stack
- Java 21
- Spring Boot
- Spring Web
- Spring Data JPA
- Validation
- PostgreSQL
- Docker
- Mailhog (for local email testing)

---

## 📦 Project Setup

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/interviewai-backend.git
cd interviewai-backend
2. Environment Configuration
Create a configuration file (application.properties or application.yml) with values appropriate for your environment.

Example variables:

properties
Copy code
spring.datasource.url=
spring.datasource.username=
spring.datasource.password=

# Server
server.port=

# Email + external service configs
⚠️ Do NOT commit real credentials or URLs.

3. Running the Project
Using Maven
bash
Copy code
./mvnw spring-boot:run
Or using Docker
bash
Copy code
docker compose up -d
📁 Project Structure
css
Copy code
src/main/java/com/interviewai
  ├── controller/
  ├── service/
  ├── repository/
  ├── entity/
  ├── dto/
  ├── config/
  └── exception/
