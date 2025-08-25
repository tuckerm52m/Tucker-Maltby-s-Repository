# Tucker-Maltby-s-Repository
# CS-230 Portfolio Artifact – Software Design Document

This repository contains my completed Software Design Document (SDD) for **The Gaming Room**, a client that wanted to expand their Android-only game *Draw It or Lose It* into a multi-platform, distributed application. This document showcases my ability to design software systems, evaluate platforms, and communicate effectively with clients and development teams.

## Reflection

### Client Summary
The client for this project was **The Gaming Room**, a company that wanted to expand its Android-only game *Draw It or Lose It* into a multi-platform application. The game is a team-based drawing and guessing competition, similar to *Win, Lose or Draw*, and the client needed a scalable, distributed design that would allow the game to run on multiple operating systems, support multiple concurrent instances, and manage users, teams, and authentication securely.

### Strengths in Documentation
One area I did particularly well was clearly organizing the design document into distinct sections—client requirements, design constraints, architecture choices, and platform evaluation. This structure made the document easy to follow for both technical team members and non-technical stakeholders. I also created UML diagrams that visually captured the system’s structure, which improved communication.

### Helpful Aspects of the Design Process
Working through the design document before writing code was helpful because it forced me to think carefully about system requirements and architectural choices in advance. By mapping out memory management, distributed systems, and design patterns (like Singleton and Iterator), I was able to write cleaner code later because I already had a roadmap.

### Revisions I Would Make
If I could revise one part of my documentation, I would refine the **platform evaluation** section. While I compared Linux, Windows, Mac, and mobile, I could have gone deeper into cloud-hosted deployment versus on-premises hosting. Expanding that section with cost analysis and performance tradeoffs would make the recommendation stronger.

### Interpreting User Needs
I interpreted user needs by focusing on scalability (supporting multiple simultaneous games), security (Basic Authentication for login), and cross-platform compatibility. Considering user needs is critical in software design because it ensures the end product is functional, user-friendly, and meets business goals rather than just being technically interesting.

### Approach to Software Design
My approach combined **top-down analysis** (starting with requirements and constraints) and **bottom-up design patterns** (like Singleton for GameService and Iterator for managing players/teams). For future projects, I would continue using UML diagrams, design patterns, and structured documentation before development, as these tools helped me organize and communicate my ideas clearly.
