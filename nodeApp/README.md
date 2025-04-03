1.	Dockerfile Creation
	•	Developed a Dockerfile to build a Node.js application image.
	•	Configured the application with a volume and custom network to ensure proper isolation and persistence.
	2.	Docker Compose Configuration
	•	Set up a docker-compose.yml file with two services:
	•	Node.js Application: Running the app on port 3000.
	•	MySQL Database: Configured with environment variables for secure access and data storage.
	3.	Volume Configuration
	•	Implemented Docker volumes for MySQL to ensure data persistence across container restarts.
	4.	Custom Network Setup
	•	Created a custom bridge network to allow secure communication between the Node.js app and MySQL database.
	5.	Environment Variables
	•	Defined environment variables for sensitive configuration (e.g., database credentials and URLs) using a .env file.
	•	Ensured that configurations like database URLs are injected securely into the application.
	6.	Documentation
	•	Documented the process and instructions on how to set up and run the application in the README.md.
	•	Included commands for building and running the containers, along with testing the connection between services.
