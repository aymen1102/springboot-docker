Steps : <br />
1 - Create Spring boot application<br />
2 - Build a simple REST API<br />
3 - Create Dockerfile<br />
4 - Build Docker Image : docker build -t springboot-docker:latest . <br />
5 - Run Docker Image in a container : docker run -p 8081:8080 springboot-docker<br />


Tutorial to make the project work locally :<br />
1 - Import the projet on your IDE<br />
2 - Build the project to generate springboot-docker-0.0.1-SNAPSHOT.jar in the target file<br />
3 - Build Docker Image : docker build -t springboot-docker:latest . <br />
4 - Run Docker Image in a container : docker run -p 8081:8080 springboot-docker<br />
5 - Test if the container is working with this URL :  http://localhost:8081/welcome
