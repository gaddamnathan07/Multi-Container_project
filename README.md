Task Management System: Multi-Container Application

Overview
This project is a Task Management System implemented as a Multi-Container Application, demonstrating modern cloud-native architecture. It enables users to effectively manage tasks with features like priority levels, due dates, and status tracking. The application showcases a full-stack development approach using ReactJS for the frontend, Spring Boot for the backend, and MySQL as the database.

The application is fully containerized using Docker to ensure consistency across environments and is orchestrated using Kubernetes, providing scalability, high availability, and robust management of resources. Designed to be deployable on any cloud platform (AWS, GCP, or Azure), this project is an excellent example of integrating containerization, orchestration, and software development best practices.




Features
Task Management:
Create, view, update, and delete tasks.
Attributes include:
Title: The name of the task.
Description: Details about the task.
Priority: Levels such as Low, Medium, and High.
Status: Track progress with statuses like To Do, In Progress, and Done.
Due Date: Specify deadlines for tasks.

Search and Filter:
Search tasks by title or description.
Filter tasks by priority, status, or due date.

User-Friendly Interface:
A responsive and dynamic frontend built with ReactJS provides a seamless user experience.

Scalable and Cloud-Ready:
Orchestrated with Kubernetes to support scaling and deployment in production-grade environments.
Suitable for deployment on cloud platforms like AWS, GCP, or Azure.




Technologies Used
Frontend:
ReactJS: For building a dynamic, responsive user interface.
Axios: To communicate with backend APIs.

Backend:
Java: Programming language for backend logic.
Spring Boot: Framework for building RESTful APIs and managing business logic.
Spring Data JPA: For interacting with the MySQL database.

Database:
MySQL: Relational database for storing user and task data.

Containerization and Orchestration:
Docker: To containerize each component (frontend, backend, and database).
Kubernetes: To deploy, manage, and scale the Multi-Container Application.
Cloud Platforms: Deployable on cloud providers like AWS, GCP, and Azure using managed Kubernetes services.
