## SOAP in Go (Without External Libraries)
# Description
This project implements a basic SOAP service and client in Go without relying on external libraries for SOAP handling. The service supports a simple "Hello, World" operation, and the client sends a SOAP request directly using HTTP.

# Technologies Used
- Go: The programming language used for both the SOAP server and client.
# Requirements
- Go 1.19 or higher.
# Installation
1. Clone the repository
Clone the repository to your local machine:
```bash
git clone https://github.com/Jimmy9812/soap_Go.git
```
2. Navigate to the project directory
Change to the project directory:
```bash
cd soap_Go
```
# Running the Application
1. Run the SOAP server
Navigate to the server/ directory and start the server:
```bash
cd server
go run server.go
```
The server will start and listen on port 8080. You should see a message like:
```
SOAP server is running on port 8080...
```
2. Run the SOAP client
In a new terminal window, navigate to the client/ directory and run the client:
```bash
cd client
go run client.go
```
The client will send a SOAP request to the server, and you should see the response:
```bash
Response from server: Hello, World!
```
