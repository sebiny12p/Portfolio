# Sebastian Paris

Developer portfolio featuring selected game, web, and software projects.

## Selected Work

### Sebio — 2D Platformer

A commercial Unity platformer built and released independently under **Sebiny Labs**. Sebio focuses on difficult encounters, nonlinear exploration, two story paths, character customisation, and local co-op.

- **Role:** Sole developer
- **Tech:** Unity, C#
- **Available on:** [Steam](https://store.steampowered.com/app/3189190/Sebio/) and [itch.io](https://sebastian12p.itch.io/sebio/) for Windows and Android
- **Source:** Private repository (available upon request)

---

### CIC CDEP — Commercial Web Application

As an intern in the Romanian Chamber of Deputies IT Department, I contributed alongside 2 teammates in creating its public visitor platform and later supported its maintenance and updates.

- **Role:** Web developer intern
- **Live site:** [cic.cdep.ro](https://cic.cdep.ro/)

> The source code and implementation details are confidential and owned by the Chamber of Deputies

---

### Playfinder — Game Discovery Platform

A web platform designed to turn game-library indecision into one launch-ready choice. It aggregates gaming libraries, standardises ownership and playtime data, and uses session length, mood, filtering, and game metadata to guide a player to one launch-ready recommendation. It also includes original multiplayer mini-games using Server-Sent Events and a progression/economy system. One of the games, Wardle, is available separately on [Github](https://github.com/sebiny12p/Wardle).

- **Role:** Full-stack developer, collaborating with a teammate on frontend refinement, bug fixes, and security improvements
- **Tech:** Node.js, Express.js, SQLite, HTML, CSS, JavaScript, Server-Sent Events
- **Live product:** [playfinder.club](https://playfinder.club/)
- **Source:** Private repository (available upon request; open-source mini-game at [Wardle](https://github.com/sebiny12p/Wardle))

---

### Navigation of a swarm of heterogeneous drones using a flocking model and airflow constraints

Research project undertaken during an Erasmus program at INSA Lyon, which included a research placement at INRIA. Developed a C++20 / Raylib 3D simulation modeling aerodynamic downwash constraints across a heterogeneous swarm (DIONE 2kg, Crazyflie Bolt 200g, Crazyflie 27g), coupled with a Hardware-in-the-Loop (HIL) flight bridge that translates simulated velocity fields into real-time control setpoints across cflib and MAVLink/PX4 interfaces under strict cage safety watchdogs.

- **Role:** Research-project developer
- **Tech:** C++, Python, cflib, MAVLink, Flocking Algorithms, Aerodynamics
> The source code and implementation details are confidential.

---

### Scrolls of Agora — Virtual Market Engine & Relational Concurrency Workbench

A relational transaction engine, multi-hub partitioned orderbook, and double-entry financial ledger across 15 normalized relations (BCNF/3NF) and 5 regional trading hubs with localized tax rates and sealed-bid kiosk auctions. Built to eliminate race-condition item duplication ("duping") across 100 concurrent threads using pessimistic row-level locking (`SELECT ... FOR UPDATE`), prevent circular-wait deadlocks via deterministic primary-key lock ordering, enforce zero-sum financial invariants ($\sum \Delta = 0$) across balanced journal accounts, and trace multi-hop wash trading using cycle-safe recursive CTEs (`WITH RECURSIVE`).

- **Role:** Sole developer
- **Tech:** PostgreSQL 17, PL/pgSQL, Python, FastAPI, psycopg Connection Pool, SQLite (WAL), Docker, HTML5 Canvas
- **Source:** [GitHub repository](https://github.com/sebiny12p/Scrolls-of-Agora)

---

### The Assembly of Pongs — Arcade Pong Game

A fast-paced retro Pong arcade game built from scratch in 100% pure 32-bit RISC Assembly. It features hardware-level memory-mapped I/O (MMIO) keyboard polling, an 80x60 VRAM framebuffer, flicker-free 60 FPS delta-rendering, paddle spin physics, and an autonomous AI opponent with 4 difficulty tiers and dynamic rally acceleration.

- **Role:** Sole developer
- **Tech:** 32-bit RISC Assembly (SCAT ISA), Computer Architecture, MMIO, Framebuffer Graphics
- **Source:** [GitHub repository](https://github.com/sebiny12p/The-Assembly-of-Pongs)

---

### The Harvest Effect — Sci-fi Farming Game

A turn-based cosmic farming game with both Java Swing and terminal interfaces. It uses an object-oriented domain model with abstract classes, interfaces, generics, custom exceptions, persistence, and automated integration tests.

- **Role:** Sole developer
- **Tech:** Java, Swing
- **Source:** [GitHub repository](https://github.com/sebiny12p/TheHarvestEffect)

---

### Ratchet & Clank: Railfinity — Procedural 3D Rail Platformer

A procedural 3D rail-grinding action platformer built in C++20 and Raylib 5.0. It features multi-lane grindrail navigation with dynamic camera tilt, jump and glide physics, upgradeable multi-weapon combat systems, and a zero-allocation engine architecture with real-time procedural audio synthesis.

- **Role:** Sole developer
- **Tech:** C++20, Raylib 5.0, OpenGL / OpenGL ES, GLSL, Android NDK
- **Source:** [GitHub repository](https://github.com/sebiny12p/Rachet_and_Clank_Railfinity)

---

### Destiny: The Flappy Ghost — Arcade Survival Flight Game

An arcade survival flight game built in C++20 and Raylib 5.0. It features procedural barrier generation, separate navigation and combat modes, six modular ability subclasses with unique movement and screen-clearing mechanics, tactical drone support, and persistent cross-platform progression.

- **Role:** Sole developer
- **Tech:** C++20, Raylib 5.0, OpenGL / OpenGL ES, Miniaudio, Android NDK
- **Source:** [GitHub repository](https://github.com/sebiny12p/Destiny_The_Flappy_Ghost)

## Contact

- GitHub: [@sebiny12p](https://github.com/sebiny12p)
- Email: Sebinylabs@gmail.com
- Studio: Sebiny Labs

*Project-specific code and assets remain in their respective repositories and distribution platforms.*
