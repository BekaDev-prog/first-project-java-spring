# First Project – Java Spring Boot

## Description

This is a basic Spring Boot web application created for Java Labs Task 1 at Vistula University.  
The app shows a greeting message and displays an image on the page using Thymeleaf.

## Technologies used

- Java 17  
- Spring Boot 3.4.5  
- Maven  
- IntelliJ IDEA  
- Thymeleaf

## Project structure

- `HelloController.java`: handles the `/hello` URL request  
- `greeting.html`: HTML page that shows the greeting text and image  
- `vistula.jpg`: image file shown on the greeting page  

## How to run

1. Open the project in IntelliJ IDEA  
2. Run the `FirstProjectJavaSpringApplication` class  
3. In the browser, go to [http://localhost:8080/hello](http://localhost:8080/hello)  
4. You will see the greeting and image  

GET http://localhost:8080/hello-text
This is a raw text response using @ResponseBody.

![App Screenshot](screenshot.png.png)
