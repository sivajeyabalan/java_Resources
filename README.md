## Java Full Stack Study Material – Repository Guide

This repository is a complete, interview-focused study kit for Java Full Stack. It covers core Java, Collections, Concurrency, IO/NIO.2, JDBC/SQL, JUnit, Web (HTML/CSS/JS), Servlets/JSP, XML/AJAX, Hibernate (JPA), Spring, and Spring Boot, with learning outcomes, sample questions, and deep-dive topic notes.

### How to use this repository

- Start with fundamentals (A → F) and proceed through backend (I, O, P, Q). Frontend (J, K, L, N) can be studied in parallel.
- Each folder includes:
  - Topic markdowns (numbered for order)
  - `Learning Outcomes/` reference
  - `Sample Questions/` for practice
- For every topic markdown, follow the consistent format: overview, definitions (WHAT/WHY/HOW/WHEN/WHERE/WHAT IF), deep-dive with runnable code, best practices, summary, and tricky interview questions.

### Folder overview

- `A. Java Fundamentals`: Language basics, types, control flow, methods, OOP intro, strings, collections intro, exceptions, packages/static/final, plus modern additions like enums/annotations/records and BigInteger/BigDecimal/formatting.
- `B. OOPS and Inheritance`: Classes/objects, constructors, static/final, inheritance/super, overriding/runtime polymorphism, encapsulation/abstraction, `instanceof`, GC/finalize/Optional, string concatenation, inner classes, and a design patterns quick tour.
- `C. Abstraction, Packages and Exception Handling`: Abstract classes, interfaces, packages, exception handling, user-defined exceptions, static/default methods in interfaces.
- `D. Wrapper Classes`: Boxing/unboxing, wrapper methods, caching/performance, `Cloneable` and `Object` methods, advanced wrapper topics.
- `E. IO Streams`: IO overview, byte/char streams, serialization, system IO/console, file operations/NIO basics, and NIO.2 advanced (Paths/Files/Channels/WatchService).
- `F. Collections`: Framework overview; List/Set/Map; iterators; lambdas/functional interfaces; Stream API; Date/Time; advanced topics: hashing/equality contracts, queues/deques/priority queues, concurrent collections and blocking queues, advanced collectors, immutability, comparators and sorting, fail-fast vs fail-safe, streams parallel pitfalls, map internals, TreeMap/TreeSet ordering edge cases, algorithms/utilities, performance, navigable APIs, WeakHashMap/IdentityHashMap, EnumSet/EnumMap, BitSet, arrays interop pitfalls, common collection patterns, and caching (Caffeine/Guava).
- `G. Junit`: Testing fundamentals, JUnit basics, annotations, asserts, suites, advanced practices, plus JUnit 5/Jupiter and Mockito essentials.
- `H. Multithreading`: Thread basics, creating threads, lifecycle and control, priorities/scheduling, synchronization/concurrency; added advanced: wait/notify, `ReentrantLock`/`Condition`, volatile/atomics/JMM, executors/thread pools, `CompletableFuture`, synchronizers (Semaphore/Latch/Barrier/Phaser), `ThreadLocal`, and `CompletableFuture` cancellation/structured concurrency.
- `I. RDBMS, SQL and JDBC`: RDBMS/Oracle intro, SQL select/sort/restrict; functions, joins, DML/DDL, DB objects/views; JDBC intro, connections/statements/prepared/result sets; transactions/batch/savepoints; callable statements; connection pooling; exceptions/resources/security; mini-project (CRUD DAO with transactions + batch); SQL injection prevention; RowSet and timeouts.
- `J, HTML`: HTML elements, tables, forms/frames, styles/div/span, HTML5 semantics, and a small mini-project.
- `K. Javascript and CSS`: CSS intro, formatting, links/lists, box model, CSS3/responsive, JS types/functions/scope, events/DOM, validation, Bootstrap, and JS/CSS mini-project.
- `L. Servlets and JSP`: Web architecture/MVC, containers/descriptors, servlet lifecycle, HTTP/request/response, ServletConfig/Context, dispatching, filters/listeners, session management, JSP basics/directives/actions, EL/JSTL, MVC best practices, file upload/download, error handling, security, i18n, build/deploy, and a mini-project.
- `M. XML I and XML II`: XML intro, DTD, namespaces, XSD, XSLT, parsing/validation (DOM/SAX/StAX), XPath/XQuery, styling XML, FO intro.
- `N. AJAX`: Concepts, XHR/Fetch, GET/POST/headers/caching/status codes, JSON/XML/FormData, DOM updates/spinners, error handling/retries/timeouts, CORS/SameSite/security, and a mini-project.
- `O. Hibernate`: ORM/Hibernate intro, configuration, entity lifecycle, fetching (lazy/eager), HQL/Criteria/JPQL, basic and collection/association mappings, caching (1st/2nd/query), transactions/concurrency, mini-project CRUD, N+1 avoidance strategies, pagination and DTO projections, optimistic/pessimistic locking, bean validation and schema generation, 2nd-level cache and filters/soft deletes.
- `P. Spring`: Framework overview, IoC/DI, bean config (XML/annotations/JavaConfig), scopes/lifecycle, autowiring/qualifiers/profiles, AOP, MVC architecture and controllers, validation/data binding, data access/transactions, testing; interview-focused additions on transactions, validation/binding, AOP, architecture patterns recap, and troubleshooting.
- `Q. Spring Boot`: Boot intro, Initializr, DI and scopes, MVC/Thymeleaf, properties/profiles/external config, entities/repositories/JPA setup/H2, REST controllers/RequestMapping/ResponseEntity, exception handling, embedded servers, mini-projects (REST+JPA+H2 and full mini-project with security/actuator/tests), actuator/metrics/observability, security/JWT/method security, testing slices/MockMvc/Testcontainers, OpenAPI/Swagger, ops/devtools/Docker, and observability with Micrometer/Prometheus/Grafana.

### Suggested study plan

1) Core Java and Collections
- A → F. Focus on: exceptions, strings, collections contracts, streams, concurrency basics.

2) Concurrency and IO
- H and E. Practice executors, synchronization, and NIO.2 file operations.

3) Data and JDBC
- I. Master prepared statements, transactions, batch, pooling, and SQL joins.

4) Web and Frameworks
- L (Servlets/JSP) then P (Spring), then Q (Spring Boot). Build the Boot mini-project.

5) ORM and Persistence
- O. Focus on mappings, fetching strategies (avoid N+1), transactions, and pagination/DTOs.

6) Frontend basics
- J and K (plus N for AJAX). Enough to integrate forms, validation, and basic UI.

7) Testing
- G. JUnit 5, Mockito, Spring Boot slices, Testcontainers.

### Running code samples

- Plain Java examples
  - Compile and run with JDK:
    ```bash
    javac MyClass.java && java MyClass
    ```
- Spring Boot samples
  - Use Maven or Gradle project structure if you port code into a Boot app. Typical commands:
    ```bash
    ./mvnw spring-boot:run
    # or
    ./gradlew bootRun
    ```

### Interview prep tips

- Prioritize scenario-based understanding: transactions across services, avoiding N+1, securing REST with JWT, paging with projections, and stream/collections pitfalls.
- Rehearse mini-project walkthroughs: architecture choices, trade-offs, and troubleshooting steps.
- Use `Learning Outcomes/` as checklists and `Sample Questions/` for drills.

### License and contributions

- Personal study use intended. Feel free to extend with your own examples and notes. If you’d like, we can add a personal “Notes/” folder to capture your summaries and flashcards.


