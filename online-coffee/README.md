# Online CoffeeShop - Product Management
![Imagen de la portada](/image/p1.jpg)

Members: Jonathan Chasipanta - Gonzalo Guachamin

This project is a microservice developed with Node.js and Express to manage products (CRUD) through a REST API.

## Requirements

- Node v20.13.1
- Docker version 26.0.0 

## Installation

1. Clona este repositorio:
    ```bash
    git clone https://github.com/JonathanP06511/P1M3-onlineCoffee.git
    ```

2. Instala las dependencias:
    ```bash
    npm install
    ```

## Usage

1. Start the server:
    ```bash
    npm start
    ```
     ```bash
      node server.js
    ```

2. Open your browser and navigate to http://localhost:3003 to view the frontend interface.
## Docker Usage

1. Build the Docker image:
    ```bash
    docker build -t image-name .
    ```

2. Run a container using the created image:
    ```bash
    docker run -p 8080:3003 -d --name container_name image_name
    ```

3. Open your browser and navigate to http://localhost:8080 to view the frontend interface.

## Endpoints

- `GET /products`: Retrieves all products.
- `POST /products`: Creates a new product.
- `GET /products/:id`: Retrieves a specific product by ID.
- `PUT /products/:id`: Updates a specific product by ID.
- `DELETE /products/:id`: Deletes a specific product by ID.

