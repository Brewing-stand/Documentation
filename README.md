# Brewing Stand Documentation 📚

Welcome to the **Brewing Stand** documentation page!

## 🚧 Work in Progress 🚧

This project is currently under development. I'm actively working on creating a powerful tool to help Minecraft modpack developers manage, create, and visualize recipes. Once completed, the documentation will provide all the information you need to set up, use, and contribute to the Brewing Stand project.

### Project Architecture

Brewing Stand follows a **microservice architecture**, where the services are independently deployed and communicate with each other. A **gateway** is typically used between the services and the front-end, which routes requests to the appropriate service.

The services currently available are:

- **[Service-Project](https://github.com/Brewing-stand/Service-Project)**: Handles project management and CRUD operations related to projects.
- **[Service-Login](https://github.com/Brewing-stand/Service-Login)**: Manages user authentication and login functionality.
- **[Service-User](https://github.com/Brewing-stand/Service-User)**: Handles user management and interaction with user data.
- **[Front-end](https://github.com/Brewing-stand/Front-end)**: The user interface where users can interact with Brewing Stand.

### Databases and Storage

- **PostgreSQL Database**: Used for storing project-related data, such as project names, descriptions, and user details.
- **Azure Blob Storage**: Used for storing project content, ensuring that all project data is stored securely.

### Project Context

Brewing Stand was developed as part of the **Advanced Software** course at **Fontys ICT**. It was a school project aimed at applying software engineering concepts in a real-world scenario. However, this project will not be continued, at least not under this organization. Future developments, if any, will likely be carried out under a different framework or structure.

Thanks for your interest in Brewing Stand! 🚀
