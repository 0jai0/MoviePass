# MoviePass 🎬

MoviePass is an online cinema ticket sales platform, designed with a microservices architecture, offering users a seamless experience to browse movies, book tickets, and receive personalized recommendations. The project employs a modern tech stack with Spring Cloud for backend microservices and React for frontend development.

## Features

- **Movie Listings**: Users can browse currently showing and upcoming movies, view detailed information, and watch trailers.
- **Cinema Ticket Booking**: Reserve cinema seats, choose showtimes, and make payments securely.
- **User Authentication**: Secure login and registration system using Spring Security and JWT.
- **Microservices Architecture**: Independent services for handling user data, bookings, movie information, and notifications.
- **Resilient System**: Circuit breaker pattern implemented with Resilience4j to ensure system reliability.
- **Distributed Tracing**: Monitor and trace requests across services using Zipkin.
- **Messaging**: Asynchronous communication between services through Kafka.
- **Caching**: Optimized performance with Redis caching.
- **Payment Gateway Integration**: Secure payments via external services.
- **Recommendation System**: Personalized movie recommendations based on user activity.

## Tech Stack

### Backend:
- **Java 17**: Core language for service implementation.
- **Spring Boot**: Simplifies microservice creation.
- **Spring Cloud**: Provides features like service discovery (Eureka), API gateway, and circuit breaker.
- **PostgreSQL**: For user and booking data.
- **MongoDB**: For movie details and history.
- **Redis**: Caching for performance optimization.
- **Kafka**: Message broker for asynchronous communication between services.
- **Docker**: Containerization of services for easy deployment.
- **Zipkin**: Distributed tracing system.
- **JWT**: For secure authentication.

### Frontend:
- **React**: For building the user interface.
- **Redux**: For managing state in the application.
- **Bootstrap**: Ensures responsive and visually appealing UI.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/moviepass.git
   cd moviepass
   mvn clean install
   npm install
   npm start
   docker-compose up --build



