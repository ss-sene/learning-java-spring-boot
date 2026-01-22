# ☕ Learning Journey: PHP to Java/Spring

> Transitioning my Backend expertise (4 years) from Symfony to the Spring Boot ecosystem.

## 🛠 Tech Stack Focus
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)

## 🎯 Objectives

## 🚀 1. Java Core & Modern Syntax (Java 21)
*Focus on the transition from PHP 8+ strict typing to Java static typing.*
- [ ] Master **Records** (Java 14+) vs Lombok for DTOs.
- [ ] Deep dive into **Stream API** & Lambdas for data manipulation.
- [ ] Understand **Optional<T>** pattern to avoid NullPointerExceptions.
- [ ] Concurrency basics: **Virtual Threads** (Project Loom) vs standard Threads.

## 🍃 2. Spring Boot Architecture (The Core)
*Mapping Symfony concepts (Service Container, Event Dispatcher) to Spring.*
- [ ] **IoC & Dependency Injection:** Mastering `@Component`, `@Service`, `@Bean`, and ApplicationContext life-cycle.
- [ ] **AOP (Aspect Oriented Programming):** Handling cross-cutting concerns (logging, transactions) via Aspects.
- [ ] **Configuration Management:** `application.yml`, Profiles (dev/prod), and `@ConfigurationProperties`.

## 💾 3. Data Persistence (JPA / Hibernate)
*Moving from Doctrine to Hibernate/Spring Data.*
- [ ] **Spring Data JPA:** Repository pattern interfaces.
- [ ] **Entity Relationships:** Mastering `@OneToMany`, fetching strategies (Lazy vs Eager), and solving the **N+1 problem**.
- [ ] **Transaction Management:** Deep understanding of `@Transactional` propagation and isolation levels.
- [ ] **Database Migrations:** Implementing **Flyway** or **Liquibase** (equivalent to Doctrine Migrations).

## 🔌 4. REST APIs & Microservices
- [ ] **Controller Layer:** `@RestController`, `@GetMapping`, RequestBodies.
- [ ] **DTO Mapping:** Using **MapStruct** for clean Entity-to-DTO conversion.
- [ ] **Error Handling:** Global Exception Handling via `@ControllerAdvice`.
- [ ] **Validation:** Integrating `jakarta.validation` (`@NotNull`, `@Size`) for strict input checking.

## 🛡️ 5. Security (Spring Security)
- [ ] **Authentication Flow:** Implementing JWT (JSON Web Tokens) & Stateless authentication.
- [ ] **Authorization:** Role-based access control (`@PreAuthorize`).
- [ ] **Password Handling:** BCrypt hashing and SecurityFilterChain configuration.

## ✅ 6. Quality & Testing (Production-Grade)
*Applying my TDD background to the Java ecosystem.*
- [ ] **Unit Testing:** JUnit 5 + **Mockito** (Mocking dependencies).
- [ ] **Integration Testing:** `@SpringBootTest` context loading.
- [ ] **Testcontainers:** Spinning up real Docker databases for reliable integration tests.

## 📦 7. Ops & Tooling
- [ ] **Build Tools:** Mastering **Maven** lifecycle and dependency management (`pom.xml`).
- [ ] **Observability:** Exposing metrics with **Spring Boot Actuator** (Health, Metrics, Prometheus).
- [ ] **Dockerization:** Building optimized Layered JAR images for Spring Boot.
