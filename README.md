# ft_trascendance - 42 Project

## **Project Description**

The **ft_trascendance** project is a web application developed using **Django** and **PostgreSQL** for the backend, **JavaScript** for the frontend, and **Docker** for deployment. The goal of this project is to create a **multiplayer 3D Pong game**. The project focuses on best practices in web development, including API creation for authentication and user management (using JWT), and real-time communication with **WebSockets**.

### **Skills Learned:**
- **Django Framework**: Developed a web application using Django, including handling HTTP requests and creating views.
- **RESTful APIs**: Implemented endpoints for user registration, authentication (JWT login), and user data management.
- **PostgreSQL Database**: Configured and integrated PostgreSQL for secure data storage.
- **Docker**: Containerized the application to ensure easy deployment in any environment.
- **WebSockets**: Used Django Channels and JavaScript to enable real-time multiplayer gameplay.
- **Three.js**: Created a 3D game environment using the Three.js library.

## **Main Features**

- **User Management**: Users can sign up, edit their profile, and retrieve their data via API.
- **Authentication**: Users authenticate using JWT tokens for secure access to protected endpoints.
- **3D Pong Game**: The game is fully rendered in 3D using **Three.js**.
- **Multiplayer Mode**: WebSockets enable real-time multiplayer gameplay.
- **Tournaments**: Local tournament mode allows multiple players to compete using the same keyboard.

## **Usage Instructions**

To set up and run the project (you will need to create som .env files):

1. Run the following command to build and start the application:
   ```bash
   make
   ```
2.  Go to the website and enjoy :)
3.  To stop the server without deleting volumes:
   ```bash
      make down
   ```
4.  To stop the server and delete all volumes:
   ```bash
      make fclean
   ```

### **Access the Website**
To access the website, go to:https://ip:8443

