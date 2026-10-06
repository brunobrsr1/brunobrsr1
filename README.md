## Hi, I'm Bruno

Final-year Computer Science student at **Instituto Superior Técnico** in Lisbon, planning to continue into the MSc with a focus on **distributed systems**. I'm drawn to infrastructure problems where one bad change can reach every machine in minutes, and I like shipping things people actually use.

### Currently building

**[fraud-scoring-platform](https://github.com/brunobrsr1/fraud-scoring-platform)** · Go  
A real-time fraud-scoring service where model promotions go through a hand-written Raft registry, so changing the live model, or rolling it back mid-incident, is ordered, durable and observable.  
**Done:** `POST /v1/score` with strict request validation and tests. **Next:** validating model artifacts on load, then Raft leader election.

**[VérticeAI](https://verticeai.pt)** · live beta  
An AI math tutor for Portuguese students preparing for the national exam. Instead of giving the answer, it asks the next right question, following the official grading criteria. Built AI-first; the product and architecture decisions are mine.

### Other projects

- **Multiplayer PacmanIST** · C, POSIX threads, named pipes · [part 1](https://github.com/brunobrsr1/PacmanIST) · [part 2](https://github.com/brunobrsr1/PacmanIST2)  
  Operating Systems project at IST. A terminal Pacman that grew into a game server: client processes connect over named pipes, a producer-consumer queue guarded by semaphores and mutexes hands sessions to a pool of manager threads, and a `SIGUSR1` handler writes the five highest-scoring players to a file.
- **[Liga Portugal Zone](https://github.com/brunobrsr1/LigaPortugalZoneWebsite)** · Java, Spring Boot, React, PostgreSQL, Docker  
  A football statistics platform fed by a Python scraping pipeline.
- **[Academic portfolio](https://github.com/brunobrsr1/ist-projects-portfolio/blob/main/ist.md)**: the rest of my coursework and projects at IST.

### Tech

Go · Java · C · Python · SQL · Spring Boot · React · PostgreSQL · Docker · Linux

### Contact

[LinkedIn](https://www.linkedin.com/in/brunobrsr) · bruno.ms1silva@gmail.com
