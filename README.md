# Microservices Project with React, Node.js, and RabbitMQ

This repository contains a microservices-based project that leverages various modern technologies to create a scalable and maintainable web application. The project is built using the following stack:

- **Frontend**: 
  - [React](https://reactjs.org/) with [Vite](https://vitejs.dev/) for fast development and optimized builds.
  - [React Bootstrap](https://react-bootstrap.github.io/) for responsive and modern UI components.

- **Backend**:
  - [Node.js](https://nodejs.org/) with [Express.js](https://expressjs.com/) for creating robust and flexible APIs.

- **Databases**:
  - [MySQL](https://www.mysql.com/) for relational data storage.
  - [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for scalable, cloud-based NoSQL database.
  - [MongoDB Compass](https://www.mongodb.com/products/compass) for local NoSQL database management and visualization.

- **Message Broker**:
  - [RabbitMQ](https://www.rabbitmq.com/) for efficient and reliable message passing between microservices.

## Project Structure

- **Frontend**:
  - Located in the `frontend` directory.
  - Built with React and Vite for a smooth development experience.
  - Uses React Bootstrap for responsive design.

- **Backend**:
  - Located in the `backend` directory.
  - Developed with Node.js and Express.js to handle API requests and business logic.
  - Connects to MySQL for relational data requirements and MongoDB for NoSQL needs.
  - Utilizes RabbitMQ for microservices communication.

## Key Features

- **Scalability**: Microservices architecture allows independent scaling of different parts of the application.
- **Modern UI**: Responsive and interactive frontend built with React and Bootstrap.
- **Flexible Data Handling**: Combines relational (MySQL) and non-relational (MongoDB) databases to meet diverse data requirements.
- **Reliable Messaging**: RabbitMQ ensures reliable communication between microservices.

## Setup and Installation

### Prerequisites

- Node.js (v14 or above)
- MySQL
- MongoDB (Atlas and Compass)
- RabbitMQ
- Docker (optional, for containerized deployment)

### Frontend

1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
