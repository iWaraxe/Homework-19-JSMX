# Homework Exercise: Writing GET and POST Requests in Java

## Overview
This homework aims to reinforce the concepts covered in our introduction to web programming, specifically focusing on HTTP methods and their implementation in Java.

## Objectives
- Develop an understanding of how to send HTTP GET and POST requests using Java.
- Gain practical experience in handling web API interactions.

## Tasks

### 1. GET Request
- Create a Java class named `HttpGetRequest`.
- Use `java.net.HttpURLConnection` to open a connection to a public API URL of your choice.
- Set the request method to 'GET'.
- Read and print the server's response to the console.

### 2. POST Request
- Create a Java class named `HttpPostRequest`.
- Open a connection to a URL using `java.net.HttpURLConnection`.
- Set the request method to 'POST' and enable output.
- Write JSON data to the request body using a `DataOutputStream`.
- Read and print the server's response to the console.

### 3. Error Handling
- Implement error handling in both `HttpGetRequest` and `HttpPostRequest` classes.
- Ensure your programs gracefully handle scenarios such as no network connection, invalid URLs, or server errors.

## Submission Guidelines
- Submit the Java source files (`HttpGetRequest.java` and `HttpPostRequest.java`).
- Ensure your code is well-commented, follows standard Java coding conventions, and includes error handling.