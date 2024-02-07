# Recipe App API

Recipe App API is a Django-based web application designed to manage recipes. It provides endpoints to perform CRUD (create, read, update, delete) operations on recipes, tags, and ingredients. The API includes user authentication to ensure secure access to protected endpoints.

## Features

- **User Authentication**: Secure user authentication using Django's built-in authentication system. Users can register, log in, and obtain authentication tokens for accessing protected endpoints.

- **Recipes Management**: Users can create, view, update, and delete recipes. Each recipe includes essential information such as title, description, cooking time, price, link, tags, ingredients, and an optional image.

- **Tags and Ingredients Management**: Users can manage tags and ingredients associated with recipes. They can create, view, update, and delete tags and ingredients.

- **Filtering and Searching**: Recipes can be filtered based on tags and ingredients, allowing users to find specific recipes easily.

- **Image Upload**: Users can upload images for recipes, enhancing the visual representation of each recipe.

- **Wait for Database Functionality**: The API includes a utility function that waits for the database to be available before starting the application. This ensures smooth startup, especially in containerized environments like Docker.

- **Docker Integration**: The application can be containerized using Docker for easy deployment and scalability.

- **Nginx Integration**: Nginx is used as a reverse proxy server to handle client requests and improve application performance.

- **Unit Tests**: Unit tests are implemented to ensure the reliability and correctness of the API endpoints.

- **API Documentation**: The API provides comprehensive documentation using Django Rest Framework's built-in documentation tool. Users can explore endpoints, request/response formats, and authentication methods through the interactive documentation.

# Deployment

The project is deployed and accessible via the following links:

- **API Documentation:** [http://ec2-54-145-131-166.compute-1.amazonaws.com/api/docs/](http://ec2-54-145-131-166.compute-1.amazonaws.com/api/docs/)
- **Admin Panel:** [http://ec2-54-145-131-166.compute-1.amazonaws.com/admin/login/?next=/admin/](http://ec2-54-145-131-166.compute-1.amazonaws.com/admin/login/?next=/admin/)

## Admin Credentials

You can access the admin panel using the following credentials:

- **Email:** admin@example.com
- **Password:** password

