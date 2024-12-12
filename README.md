# Premier League Player Stats

## Description

This is a simple Spring Boot application that retrieves Premier League player stats from a PostgreSQL database. This application is designed to demonstrate how to use Spring Boot and PostgreSQL together to build a RESTful API.

## Technologies

- Spring Boot
- PostgreSQL
- Java

## Installation

1. Clone the repository
2. Open the project in your preferred IDE
3. Run the application

## Usage

1. Create a PostgreSQL database and table with the CSV file provided
2. Modify the `application.properties` file with your PostgreSQL connection details
3. Run the application
4. Access the application at `http://localhost:8080/api/v1/player` to retrieve all players stats
5. Access the application at `http://localhost:8080/api/v1/player/{playerName}` to retrieve player stats for a specific player
6. Access the application at `http://localhost:8080/api/v1/player/{nation}` to retrieve player stats for a specific nation
7. Access the application at `http://localhost:8080/api/v1/player/{position}` to retrieve player stats for a specific position
8. Access the application at `http://localhost:8080/api/v1/player/{team}` to retrieve player stats for a specific team

## Next Steps

- Frontend development
- Integration with a frontend framework
- Deployment to a cloud platform
- Testing and debugging