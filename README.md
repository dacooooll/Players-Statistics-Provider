# Player Stats & Leaderboard Service
//Methodology to follow;
A backend REST API project built for a game using Java and Spring Boot. This is my 2nd-year B.Tech Computer Science mini project to learn how backend services, databases, and REST APIs work.
## Tech Stack
- **Language:** Java 17
- **Framework:** Spring Boot 3
- **Database:** MongoDB
- **Tools:** Maven, VS Code
  
## Features Implemented
- Player CRUD operations (Register, Get, Update, Delete)
- Record match results (Wins/Losses, Scores)
- Track player match history
- Leaderboard sorted by total score using MongoDB queries
- Input validation and global error handling
- Actuator health check endpoints
  
## How to Run Locally
1. Make sure you have Java 17 and Maven installed.
2. Set up your MongoDB connection string in `src/main/resources/application.properties`.
3. Run the application using Maven:
   ```bash
   mvn spring-boot:run
