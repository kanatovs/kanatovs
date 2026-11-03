# Hi, I'm Sabyrzhan

I'm **Sabyrzhan Kanatov**, a Software Engineering student at **Astana IT University**, focused on **Go backend development**. I build REST APIs with explicit business rules, SQL persistence, and automated tests.

**Backend stack:** Go · SQL · PostgreSQL / pgx · Redis · HTTP / REST · JWT · Docker Compose · OpenAPI · GitHub Actions.

## Featured project

[![CI](https://github.com/kanatovs/taskflow-api/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/kanatovs/taskflow-api/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/kanatovs/taskflow-api?label=release)](https://github.com/kanatovs/taskflow-api/releases/latest)

**[TaskFlow API](https://github.com/kanatovs/taskflow-api)** is a Go REST API for collaborative project and task management.

- Projects, tasks, and comments with JWT authentication, bcrypt password hashing, project roles, filtering, and pagination.
- PostgreSQL with pgx, parameterized SQL, transactions, and versioned migrations; request deadlines propagate through the application layers.
- Project access is checked before cached detail reads. Optional Redis caching uses TTL and invalidation, with PostgreSQL fallback when Redis is unavailable.
- Docker Compose and OpenAPI, with unit, integration, race, migration, and smoke checks; GitHub Actions runs Go and database verification.

[Quick start](https://github.com/kanatovs/taskflow-api#local-setup-windows-powershell) · [OpenAPI](https://github.com/kanatovs/taskflow-api/blob/main/docs/openapi.yaml) · [Architecture](https://github.com/kanatovs/taskflow-api/blob/main/docs/architecture.md) · [Testing guide](https://github.com/kanatovs/taskflow-api/blob/main/docs/testing.md)

## Other selected projects

| Project | Focus |
| --- | --- |
| [Airline API](https://github.com/kanatovs/airline-api) | Java / Spring Boot flight API with validated DTOs, PostgreSQL, Flyway migrations, and integration checks. |
| [Aitunavi](https://github.com/kanatovs/Aitunavi) | Kotlin / Jetpack Compose student app with offline schedules, teacher search, notes, and lesson reminders; Android tests and CI. |
| [Java Algorithms](https://github.com/kanatovs/assignment1-divide-and-conquer) | Sorting, selection, and closest-pair algorithms with correctness checks, complexity analysis, measurements, and plots. |
| [Smart Calculator](https://github.com/kanatovs/smart-calculator) | Python / Tkinter calculator with validated results, operation history, and atomic JSON/CSV writes that preserve existing files on write failure. |
| [Music Band](https://github.com/kanatovs/music-bandv3) | Responsive HTML / CSS / JavaScript fan archive with Bootstrap, gallery filters, and demo form validation. [Live site](https://kanatovs.github.io/music-bandv3/). |

In team projects, my contributions include the calculator logic, history storage, validation, and original tests in **Smart Calculator**, and the homepage, contact page, gallery filter, carousel, and form validation in **Music Band**.

## Current focus

I'm deepening my understanding of Go concurrency, SQL transactions, cache consistency, and backend testing through practical projects.

## Contact

Open to backend internship opportunities.

**Email:** [kanatovsakosh@gmail.com](mailto:kanatovsakosh@gmail.com) · **Phone:** +7 778 826 5028
