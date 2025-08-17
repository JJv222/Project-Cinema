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

## Pictures  
Here are some example screenshots of the system in action:  

<img width="2539" height="1180" alt="Zrzut ekranu 2025-08-16 152259" src="https://github.com/user-attachments/assets/81e6c3b7-ac20-4558-b5da-e467b1ed9a83" />
<img width="2550" height="939" alt="Zrzut ekranu 2025-08-16 152445" src="https://github.com/user-attachments/assets/e6ede7d4-c7cf-49a0-a1f5-3882ccc4ec56" />
<img width="2521" height="1026" alt="Zrzut ekranu 2025-08-16 152509" src="https://github.com/user-attachments/assets/5f0cab8c-735a-4892-b844-afcc19805371" />
<img width="2549" height="1037" alt="Zrzut ekranu 2025-08-16 152547" src="https://github.com/user-attachments/assets/fef6d88c-6bcb-4a1f-8b25-cf26838adce4" />
<img width="2533" height="758" alt="Zrzut ekranu 2025-08-16 164411" src="https://github.com/user-attachments/assets/c1fc5fe6-6e66-476f-b610-bf5c24b2adbf" />
