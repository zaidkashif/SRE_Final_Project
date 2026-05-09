# SRE Final Project - Context and Progress

## Project Overview
The project involves Re-Engineering a Legacy Hospital Management System and performing code analysis on an open-source Java project. It is divided into 7 main parts (A to G), focusing on Code Smell Analysis, Refactoring, Coupling, Dynamic Analysis, Database Smell Detection, Normalisation, and Data Migration.

## Parts Checklist
- [x] **Part A — Project Initialisation and Tool Setup:** Select a Java project (≥2000 LOC, ≥6 classes), set up SonarQube via Docker, Python Tutor, Draw.io, and a DB.
    - **Selected Project:** `apache/commons-cli` (8,746 LOC, 87 classes)
    - **SonarQube:** `docker-compose.yml` created.
    - **Database:** PostgreSQL configured via Docker & Prisma Initialized.
- [ ] **Part B — Code Smell Analysis and Refactoring:** SonarQube metrics extraction, identifying 5 categories of code smells (Bloaters, OO-Abusers, Change Preventors, Dispensables, Couplers), and demonstrating refactoring.
- [ ] **Part C — Dependency, Coupling and Technical Debt:** Afferent/Efferent coupling calculation, Instability metric, Technical Debt assessment, and remediation cost calculation.
- [ ] **Part D — Dynamic Program Analysis:** Execution trace via Python Tutor, CFG diagram, and AST inspection using astexplorer.net.
- [ ] **Part E — Data Smell Detection (Prisma ORM):** Identify data smells in the provided legacy hospital schema and prioritise them based on hospital risks.
- [ ] **Part F — Schema Normalisation and Refactoring (Prisma ORM):** Normalise `pat_master` to 3NF, apply 5 specific refactoring scripts using Prisma migrations.
- [ ] **Part G — Data Migration Design and Execution:** ETL pipeline to migrate legacy CSV data to the newly refactored schema, using Python and Prisma Client for validation.

## Current Status
- Project requirements analysed.
- Pending answers from the user regarding the selection of the Java project and tool availability (like Docker for SonarQube).
