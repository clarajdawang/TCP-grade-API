# TCP grade API
This project implements a Python-based client/server application using TCP socket programming that allows authenticated users to retrieve course grade information securely over a network. The system demonstrates practical use of sockets, client-server architecture, and secure password handling with SHA-256 hashing.

## Key Features:
- TCP Socket Programming: Handles client-server communication efficiently over the network.
- Client/Server Architecture: Separate Python applications for server and client operations.
- Authentication: Students authenticate with a hashed ID/password before accessing grades.
- Grade Retrieval: Clients can query individual lab grades, midterm averages, or full grade records.
- CSV-based Database: Server reads grades from a CSV file, demonstrating structured data handling.
- Command-based Interface: Easy-to-use terminal commands for requesting grade data.
