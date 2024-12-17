# Products REST API

This is a simple **RESTful API** built with **Node.js** and **Express** that uses a **SQLite** database to manage product data. It allows users to perform CRUD (Create, Read, Update, Delete) operations on product records.

---

## Features

- **GET**: Retrieve all products or a single product by ID.
- **POST**: Add a new product.
- **PUT**: Update an existing product by ID.
- **DELETE**: Delete a product by ID.
- Uses **SQLite** as the database.
- Lightweight and easy to set up locally.

---

## Technologies Used

- **Node.js**: JavaScript runtime for server-side development.
- **Express**: Web framework for building APIs.
- **SQLite**: Lightweight database for storing product records.
- **REST Client**: (Optional) Tool for testing API endpoints in VS Code.
- **Docker**: For containerizing the application.
- **Kubernetes**: For managing the application using clusters.

---

## Setup and Installation

Follow these steps to set up the project on your local machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/products-api.git
   cd products-api

---   

## Dockerization and Kubernetes Deployment

- **Dockerized Application**: The REST API has been containerized using Docker, providing an isolated, consistent runtime environment that can be easily deployed across various systems.
  - Dockerfile created to build the application image, set dependencies, and run the app inside a container.
  - The image has been pushed to Docker Hub for easy access and deployment.


- **Kubernetes Cluster**: Deployed the Dockerized API to a Kubernetes cluster, ensuring efficient management and scalability
  - Deployment: A Kubernetes Deployment was created to ensure high availability by running multiple replicas of the application.
  - Service: A Kubernetes Service was set up to expose the API externally, allowing communication from outside the cluster using a LoadBalancer type.
  - Auto-scaling and Monitoring: With Kubernetes, the API can be easily scaled based on demand, ensuring optimal performance under varying loads.

   
