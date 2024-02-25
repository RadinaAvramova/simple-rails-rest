# SIMPLE RAILS 5 REST API
Welcome to the SIMPLE RAILS 5 REST API project! This project provides a simple example of building a RESTful API using the Ruby on Rails framework. With this API, you can perform basic CRUD (Create, Read, Update, Delete) operations on a resource.

## Features
1. **RESTful Endpoints:** Implements RESTful endpoints for creating, reading, updating, and deleting resources.

2. **Database Integration:** Integrates with a database to store and retrieve resource data.

3. **JSON Responses:** Returns JSON responses for API requests to facilitate communication with client applications.

4. **Authentication and Authorization:** Provides optional authentication and authorization mechanisms for securing API endpoints.

## Installation
To run the SIMPLE RAILS 5 REST API locally, follow these steps:

1. **Clone the Repository:** Clone the repository to your local machine using the following command:

git clone https://github.com/RadinaAvramova/simple-rails-rest.git

2. **Navigate to the Directory:** Change your current directory to the location of the cloned repository:

cd simple-rails-rest

3. **Install Dependencies:** Ensure that you have Ruby and Rails installed on your machine. Then, install the required dependencies by running:

bundle install

4. **Database Setup:** Set up the database by running the following commands:

rails db:create

rails db:migrate

5. **Start the Server:** Start the Rails server by running:

rails server

6. **Access the API:** Once the server is running, you can access the API endpoints by sending HTTP requests to the appropriate URLs.

## Usage
1. **Create:** Use HTTP POST requests to create new resources. Send JSON data in the request body to specify the resource attributes.

2. **Read:** Use HTTP GET requests to retrieve existing resources. Specify the resource ID in the URL to retrieve a specific resource.

3. **Update:** Use HTTP PATCH or PUT requests to update existing resources. Send JSON data in the request body to specify the updated attributes.

4. **Delete:** Use HTTP DELETE requests to delete existing resources. Specify the resource ID in the URL to delete a specific resource.

5. **Authentication and Authorization:** If authentication and authorization are enabled, include appropriate credentials or tokens in the request headers to access protected endpoints.

## Customization
You can customize the SIMPLE RAILS 5 REST API by modifying aspects such as the resource model, controller actions, database schema, and authentication mechanisms. Additionally, you can add new features, implement data validation, or integrate with external services as needed.
