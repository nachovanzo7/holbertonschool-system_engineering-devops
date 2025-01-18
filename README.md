![task0 drawio](https://github.com/user-attachments/assets/8c07b85a-d4bf-471e-b4c8-df2e704c0cdb)

Components Explained
1. What is a Server?
A server is a computer or system that provides resources, services, or data to other devices (clients) over a network. In this case, it hosts the web application and processes user requests.

2. What is the Function of the Domain Name?
The domain name (foobar.com) is a human-readable address for the server's IP address. It allows users to access the website without remembering the IP.

3. What Type of DNS Record is www in www.foobar.com?
The www in www.foobar.com is an A record (Address Record) in the DNS system. It maps the subdomain www to the IP address 8.8.8.8.

4. What is the Function of the Web Server?
The web server (Nginx):

Handles incoming HTTP/HTTPS requests.
Serves static files like images, CSS, or JavaScript.
Passes dynamic requests to the application server.
5. What is the Function of the Application Server?
The application server:

Processes the business logic of the application.
Interacts with the database to fetch or store data.
Constructs the dynamic content (e.g., HTML, JSON) to send to the client.
6. What is the Role of the Database?
The database (MySQL) stores structured data, such as:

User credentials.
Product information.
Transaction records.
The application server queries this data to serve dynamic content.
7. How Does the Server Communicate with the User’s Computer?
The server uses the HTTP/HTTPS protocol to send responses back to the user's browser. Data is transmitted via the TCP/IP stack over the internet.

