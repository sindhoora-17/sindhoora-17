## Hi, I'm Sindhoora 👋

Software engineer with an M.S. in Computer Science from DePaul University, interested in backend, distributed systems, and full-stack development. I enjoy building systems end to end and digging into the parts that make them reliable — concurrency, queues, persistence, failure recovery, APIs, testing, and performance.

📫 Reach me: rnslsindhura@gmail.com · [LinkedIn](https://www.linkedin.com/in/sindhoora-rnsl/)

## Technologies
- **Languages:** Go, Java, Python, TypeScript, JavaScript, C#, SQL
- **Backend & Distributed:** Spring Boot, ASP.NET Core, FastAPI, REST APIs, gRPC, Protocol Buffers
- **Frontend:** React, TypeScript, Vite, Tailwind CSS
- **Data & Infrastructure:** PostgreSQL, Redis, MySQL, SQLite, Docker, Docker Compose
- **AI / Retrieval:** RAG, hybrid retrieval (BM25 + vector), FAISS, LangChain, embeddings
- **Tools & Testing:** Git, GitHub Actions, Maven, JUnit, k6

## Featured Projects

### TaskForge — Distributed Job Execution Platform
Distributed background job platform built in Go with PostgreSQL and Redis Streams. Implements concurrent worker pools, horizontal worker scaling, automatic retries with exponential backoff, execution timeouts, worker heartbeats, crash recovery, dead-letter handling, duplicate-execution protection, and a transactional outbox for reliable job delivery. A local k6 benchmark with two worker processes and eight concurrent consumers completed 1,246 jobs at 41.26 jobs/second with a 0% HTTP request failure rate. — *Go, PostgreSQL, Redis Streams, Docker, Docker Compose, k6*

### Gearwood — Full-Stack E-Commerce Platform
Full-stack e-commerce application built with Spring Boot featuring product browsing, cart and checkout flows, order management, transactional checkout, a swappable payment abstraction, line-item snapshotting, and role-based access control with Spring Security. — *Java, Spring Boot, Spring Security, Spring Data JPA, Thymeleaf, MySQL*

### DocuQuery AI — Document Q&A with Hybrid Retrieval
Document question-answering system that combines BM25 keyword retrieval with FAISS vector search using Reciprocal Rank Fusion. Answers questions over PDFs with page-level citations and includes an evaluation harness for measuring retrieval quality. — *Python, FastAPI, LangChain, FAISS, BM25, Gemini*

### Distributed Inverted-Index Search Engine
Distributed document search engine where multiple clients process document collections in parallel and communicate with a central server using gRPC and Protocol Buffers. Includes concurrent indexing, thread-safe aggregation, boolean search, and performance benchmarking across client counts. — *Java, gRPC, Protocol Buffers, TCP Sockets, Maven*

### ActivityHub — Personal Activity Timeline
Full-stack application that combines activity from Spotify, GitHub, Google Calendar, and Discord into a unified timeline, including OAuth 2.0 authentication, automatic provider token refresh, response normalization, and deduplication. — *React, ASP.NET Core, EF Core, SQLite, OAuth 2.0*

## Currently Exploring
- Distributed systems and backend engineering
- Reliability and asynchronous processing
- Full-stack application development
- Applied AI and retrieval systems
