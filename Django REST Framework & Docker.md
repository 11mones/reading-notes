# Docker
### What is Docker?


Docker is an open-source platform that enables developers to automate the deployment and management of applications using lightweight
containers, promoting consistency, scalability, and portability.

**Key components of a Docker container:**

* Docker Image: Lightweight, standalone package with everything needed to run an app.

* Container: Running instance of a Docker image, providing isolation and portability.

* Dockerfile: Text file with instructions to build a Docker image.

* Docker Engine: Core tool for creating and managing Docker containers.

* Docker Registry: Repository for storing and sharing Docker images.

### How Docker streamlines development and deployment:

* Isolation: Containers ensure independence and prevent conflicts.

* Portability: Apps run consistently across different environments.

* Scalability: Easy to scale applications with container orchestration.

* Fast Deployment: Lightweight images enable quick start-up and movement.

* Version Control: Images are version-controlled for consistency.

* Dependency Management: All dependencies are packaged within the container.


# Building a library website using Django

**Building a library website using Django involves setting up a Django project, defining database models for library entities, writing
views to handle user requests, designing HTML templates for data display, implementing user authentication if needed, and deploying
the application for public access. Django's robust framework streamlines development, ensuring a functional and user-friendly library
website.**


### How to build a functional and efficient library website using Django.
* Set up the Django project and configure the database.
* Define and create database models to represent library entities.
* Write views to handle user requests and provide responses.
* Design HTML templates to display dynamic data from the views.
* Map URLs to the appropriate views using URL patterns.
* Implement user authentication for secure access if required.
* Organize and manage static files for CSS, JavaScript, and images.
* Test the website's functionality using unit tests.
* Deploy the Django application on a web server for public access.






# Differences between Django and Django REST framework?


### **Django:**


*Full-fledged web framework for building web applications.*



*Used to create traditional websites with HTML views, templates, and forms.*



*Views are used to handle HTTP requests and render HTML templates.*



*Utilizes forms for data validation and user input in web applications.*



*Provides built-in authentication and permission systems for web apps.*



*URL patterns are used to route requests to appropriate views.*



*Primarily deals with HTML templates and responses for web pages.*




### **Django REST:**


*Extension of Django focused on building Web APIs.*



*Specializes in developing RESTful APIs for various clients.*



*Views handle HTTP methods like GET, POST, PUT, DELETE for API data.*



*Utilizes serializers to convert complex data (e.g., Django models) into JSON or other content types suitable for API responses.*



*Extends Django's authentication and permission system for secure API access.*



*Uses URL routing to map API endpoints to corresponding views.*



*Provides responses in various formats like JSON, XML, etc., suitable for API interactions.*
