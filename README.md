# Angular & Java Spring Fullstack Cinema Ticket Booking System  

The Cinema Ticket Booking System is a full-stack web application created with an **Angular frontend** and a **Java Spring Boot backend**. It includes a **PostgreSQL database** for persistent data management and is fully containerized using **Docker** for easy deployment.  

## Project Description  
The application enables cinema customers to **browse the movie schedule, book tickets, and reserve seats**, while cinema staff (ticket inspectors) can **validate and manage ticket states**. The system provides an intuitive seat selection interface, ticket verification by unique code, and secure access control for staff operations.  

## Features  

### General Features  
- **Browse Movie Repertoire**: Guests can explore available movies, showtimes, descriptions, and images without logging in.  
- **Seat Reservation**: Customers can select seats using a graphical hall layout and purchase tickets if seats are available.  
- **Unique Reservation Code**: Each booking generates a code used as proof of purchase.  

### Ticket Management  
- **Ticket States**: Tickets can be *valid*, *used*, *expired*, or *non-existent*.  
- **Time Validation**: Tickets remain valid until 15 minutes before the showtime and expire after the movie ends.  
- **Inspector Features**: Logged-in cinema staff can check ticket status, view reserved seats, and mark tickets as used.  

## Technologies  
- **Frontend**: Angular with TypeScript for interactive UI  
- **Backend**: Java Spring Boot for API development and business logic  
- **Database**: PostgreSQL for persistent storage  
- **Deployment**: Docker & Dockerfile for containerized services  
- **Security**: Role-based access (guests vs. inspectors)  

[![My Skills](https://skillicons.dev/icons?i=idea,java,spring,ts,angular,postgres,docker)](https://skillicons.dev)  
