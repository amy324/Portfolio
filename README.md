# Portfolio

Welcome to my portfolio page!

🔗 My GitHub serves as a curated showcase of projects, ranging from larger-scale applications to compact yet impactful microservices and skill-specific demonstrations. Most projects here use Golang, as it is my favourite language to use (mostly due to the fact that it compiles direcrtly to machine code and its efficency).

Every project here, whether in the large-scale or microservices/demonstrative section, includes detailed documentation. This comprehensive documentation leads you through methodologies, code insights, and usage instructions step by step. Embracing open source ethos, I've consciously integrated mainly open source and free software, frameworks, and tools into my projects to ensure accessibility - this along with how the documentation is structured, allows for each project to be replicated and customized, illustrating how these creations can serve as robust foundations for professional ventures with minor adjustments, such as transitioning from Render to AWS for deployment etc.

Each public project on my profile has been specially crafted to serve as portfolio pieces. Please note, my professional work for clients is set to private as these remain confidential. However, [this repository](https://github.com/amy324/Professional-Project-Details) contains detailed case studies for three professional projects that I have worked on. While the actual products developed for these projects are confidential and cannot be shared publicly, I have been granted permission to share these comprehensive write-ups outlining the project objectives, technologies used, key features, and integrations. The case studies provide insights into the project scope, technologies utilized, and strategies employed, without revealing sensitive information.

[Explore my GitHub profile](https://github.com/amy324)

## Contents

Click to view the summary of a specific project, or keep scrolling to see all:

### Large-Scale Projects

| Project | Tech|
|----------|----------|
| **[Ticket Raising Platform Backend](#ticket-raising-platform-backend)**   | Gorilla/Mux, MySQl, JSON Web Tokens, bcrypt, Render, Mailtrap, net/http, validation, authentication, RESTful APIs, CRUD operations   |
| **[Steam Games Data CLI App](#steam-games-data-cli-app)**   | Web Scraping, Goquery, Cobra, Encoding, JSON parsing, CSV parsing, regex, os/exec, bufio, bytes, net/http   |
| **[Blogging Platform Infastructure](#blogging-platform-infastructure)**   | IaC, Terraform, HCL, Prometheus, Docker, Golang, Gin, ORM, PostgreSQL |
| **[Advanced Data Analysis CLI Framework](#advanced-data-analysis-cli-framework)**   | MySQL, Cobra, Python, Python, pandas, sklearn Machine Learning, os/ex    |


### Microservices/Demonstrative Projects

| Project | Tech|
|----------|----------|
| **[Port Scanner](#port-scanner)** | Python, Socket Programming, CLI, TCP, IP Address Scanning, Network Troubleshooting, Monitoring, Networking Protocols, Date and Time Handling, ASCII Art |
| **[CI/CD Pipeline Automation Tool](#ci-cd-pipeline-automation-tool)**   |CI/CD Pipeline Automation, Cobra, yaml, Go-Git  |
| **[Concurrent Task Scheduler](#concurrent-task-scheduler)** | Concurrency, Pointers, Goroutines, Mutexes, Logrus, sync, testing  |
| **[Markdown to HTML Microservice](#markdown-to-html-microservice)**  | Regex  |
|   **[URL Shortener Microservice](#url-shortener-microservice)**  | Redis, Gorilla/Mux, Godotenv, Encoding/JSON, net/http, os, Render, httptest, testing, APIs   |
|**[Fake Payment Gateway Microservice](#fake-payment-gateway-microservice)** |  PostgreSQL, Encoding/json, net/http, Goluhn, Gorilla/Mux, Lib/pq, validation |
| **[Monte Carlo Pi Simulator](#monte-carlo-pi-simulator)**  | Concurrency, Modular Structure, Gonum/Plot    |
| **[CSV Parsing CLI Tool](#csv-parsing-cli-tool)**  | PostgreSQL, Lib/pq, Encoding/csv, os, Cobra, strconv   |
| **[Classic Computer Science Problems Series](#classic-computer-science-problems-series)**    | Concurrency, Pointers, Goroutines, Channels, Randomized, Time-Based, Mutexes, Synchronization, Algorithm, testing, Buffer  |
| **[CLI To-Do List App](#cli-to-do-list-app)** |CRUD (Create, Read, Update, Delete) operations, bufio, os, strconv  |
| **[Golang Weather CLI App](#golang-weather-cli-app)**  |Data structures, JSON response, API calls, encoding/json, flag, io, net/http, net/url |
| **[Golang RESTful API Demo](#golang-restful-api-demo)**  |RESTful API, encoding/json, net/http, Gorilla/Mux  |

---

## Large-Scale Projects

### Ticket Raising Platform Backend
**Tech: Gorilla/Mux, MySQl, JSON Web Tokens, bcrypt, Render, Mailtrap, net/http, validation, authentication, RESTful APIs, CRUD operations**

A comprehensive backend system demonstrating best practices in Golang development, including user authentication, ticket management, real-time communication, and email notifications.

**Key Features**:
- User Authentication and Authorization: Token-based authentication and authorization mechanisms using JSON Web Tokens (JWT).
- Ticket Management: Endpoints for CRUD operations on support tickets, categorized and tracked efficiently.
- Real-Time Communication: Messaging features embedded within ticket threads.
- Email Notifications: Notifies users about ticket updates and relevant events, utilizing Mailtrap for testing purposes.
- Data Persistence and Management: Utilizes MySQL for storing and managing data.


[Explore Ticket Raising Platform Backend](https://github.com/amy324/Ticket-Raising-Platform-Backend)

### Steam Games Data CLI App
**Tech: Web Scraping, Goquery, Cobra, Encoding, JSON parsing, CSV parsing, regex, os/exec, bufio, bytes, net/http**

A command-line tool written in Go for scraping game data from the Steam store. This project serves as a portfolio piece showcasing web scraping, JSON and CSV file handling, concurrent HTTP requests, and command-line interface (CLI) implementation using Cobra.

The Steam Games Data CLI App allows users to access and explore information about games available on the Steam  platform through a streamlined command-line interface. Leveraging web scraping techniques, the application retrieves valuable data such as game titles, prices, release dates, reviews, tags, developers, and publishers, as well a system requirements directly from the Steam store website.

**Key Features**:

- Game Data Retrieval: The application utilizes goquery and scrapes data from the Steam store website, including game titles, prices, release dates, reviews, and tags. It exports this data to both a JSON and CSV file as `games.csv` and `games.json`, respectively. 
- User Interaction: Users can interact with the application through a command-line interface (CLI), providing keywords to search for specific games and selecting actions such as opening JSON or CSV files directly from the command-line.
- Detailed Information: Users can access detailed information about individual games, including developer, publisher, description, and system requirements.
- Additional Details: Prompt the user to input a game link for scraping additional details such as developer, publisher, description, and system requirements.
- Compliance: The application ensures compliance with the Steam Data Terms of Use, respecting user privacy and data handling practices outlined by Valve Corporation.

[Explore Steam Games Data CLI App](https://github.com/amy324/Steam-Games-Data-CLI-App)

## Blogging Platform Infastructure
**Tech: IaC, Terraform, HCL, Prometheus, Docker, Golang, Gin, ORM, PostgreSQL**

A blogging platform infrastructure designed with a focus on reliability, scalability, and observability, following best practices of Site Reliability Engineering (SRE). This project implements the infrastructure for a simple blogging platform using Docker containers orchestrated with Terraform. The platform includes a RESTful API for managing posts, PostgreSQL for storing data and utilizes Prometheus for monitoring purpose

**Key Features**:

- **Containerization**: The application components are containerized using Docker, providing consistency and isolation across environments.
- **Orchestration**: Terraform is used for infrastructure as code (IaC) to define and manage the deployment of Docker containers, ensuring consistency and reproducibility of the infrastructure setup.
- **Monitoring**: Prometheus is integrated into the infrastructure to collect and store application metrics, allowing for real-time monitoring and alerting on key performance indicators (KPIs) and service-level objectives (SLOs).
- **Automation**: The infrastructure setup is automated using Terraform, enabling seamless provisioning, scaling, and teardown of resources, reducing manual intervention and human error.
- **Resilience**: The platform is designed with fault tolerance and redundancy in mind, utilizing features such as container health checks, automatic container restarts, and database replication for data durability.
- **Scalability**: The infrastructure architecture supports horizontal scalability, allowing for dynamic scaling of application instances based on demand using Docker Swarm or Kubernetes in production environments.

[Check Out The Project Here](https://github.com/amy324/Blogging-Platform-Infrastructure)

### Advanced Data Analysis CLI Framework
**Tech: MySQL, Cobra, Python, Python, pandas, sklearn, os/ex**

A versatile and scalable framework tailored for conducting fully customizable sophisticated data analysis tasks through a command-line interface. Its design and functionality closely resemble a custom program I developed for a client, showcasing its adaptability and effectiveness in real-world scenarios.

**Key Features**:
- Modular Structure: Scalable and maintainable with distinct modules.
- Database Interaction: Seamless connection to MySQL databases for storing and retrieving results.
- Customizable Analysis & Python Script Integration: Users can run custom scripts, integrating Python or Golang commands.
- Includes an completed Python script as an example which performs logistic regression analysis after parsing CSV data.
- Machine Learning with sklearn in Python script.
- Command-Line Interface: Utilizes Cobra library for user-friendly interactions.


[Explore Advanced Data Analysis CLI Framework](https://github.com/amy324/CLI-Framework-for-Advanced-Analysis)

## Demonstrative Projects/Microservices 

### Port Scanner
**Tech: Python, Socket Programming, CLI, TCP, IP Address Scanning, Network Troubleshooting, Monitoring, Networking Protocols, Date and Time Handling, ASCII Artt**

This port scanning tool is a Python script designed to aid in tasks such as network troubleshooting and security auditing tasks. Leveraging Python's socket programming capabilities, it scans for available ports on a specified target IP address, providing insights into the availability and status of network services.

**Key Features**:
- Comprehensive Port Scanning: Scans for available ports within a specified range (1-65535) on the target IP address.
- Network Troubleshooting: Helps identify network connectivity issues and misconfigured network devices.
- Security Auditing: Assists in assessing the security posture of network infrastructure by identifying open ports and potential vulnerabilities.
- Command-line Interface: Allows easy execution from the command line, with the target IP address specified as a command-line argument.
- Timestamp Logging: Displays the timestamp when the scanning process started, aiding in tracking and analysis.
- Visually Appealing Output: Incorporates ASCII art banners generated by the pyfiglet library for a visually appealing user experience.


[Explore the Port Scanner on GitHub](https://github.com/amy324/Port-Scanner)
### CI-CD Pipeline Automation Tool
**CI/CD Pipeline Automation, Cobra, yaml, Go-Git.**

A command line tool for automating Continuous Integration and Continuous Deployment (CI/CD) pipelines for Go projects.

**Key Features**

- Configuration: Easily configure CI/CD pipeline settings such as repository URL, branch name, and test script command.
- Automation: Automate the execution of CI/CD tasks including fetching source code, running tests, and deploying artifacts.
- Customization: Customize CI/CD workflows by specifying test scripts tailored to your project's needs.
  
[View the Project here](https://github.com/amy324/CI-CD-Pipeline-Automation-Tool)

### Concurrent Task Scheduler
**Tech: Concurrency, Pointers, Goroutines, Mutexes, Logrus, sync, testing.**

Executes multiple tasks concurrently while limiting the maximum number of tasks running simultaneously.

**Key Features**:
- Concurrent Execution: Execute multiple tasks concurrently, maximizing resource utilization.
- Concurrent Limit: Limit the maximum number of tasks running simultaneously to prevent resource exhaustion.
- Logging: Utilize the Logrus package for structured logging, enabling detailed logging of task execution.

[Check out the Concurrent Task Scheduler here](https://github.com/amy324/Concurrent-Task-Scheduler)


### Markdown to HTML Microservice
**Tech: Regex**

This is a microservice written in Golang that converts Markdown syntax to HTML. It provides a function `MarkdownToHTML` that takes Markdown content as input and returns the corresponding HTML content. The `main.go` file contains the logic for converting Markdown to HTML. It defines the `MarkdownToHTML` function, which takes Markdown content as input and uses regular expressions to identify and replace Markdown syntax with corresponding HTML tags. This includes handling headings, bold and italic text, unordered and ordered lists, links, and images.
Includes an example Markdown in `func main` - feel free to replace with any Markdown text to convert to HTML. Documentation provides expected terminal output.

[Click here for the Markdown to HTML Microservice](https://github.com/amy324/Markdown-To-HTML-Microservice.git)

### URL Shortener Microservice
**Tech: Redis, Gorilla/Mux, Godotenv, Encoding/JSON, net/http, os, Render, httptest, testing, APIs**

A powerful backend microservice built in Golang, designed to shorten long URLs into more manageable links, redirecting users seamlessly to their intended destinations. Leveraging Gorilla Mux for routing and Redis for efficient storage and retrieval of URL mappings, this microservice ensures fast and reliable URL shortening functionality.

**Key Features**:
- Efficient URL Shortening: Generate short, easy-to-share URLs for long web addresses.
- Seamless Redirection: Direct users from short URLs to their corresponding long URLs effortlessly.
- Robust Backend Architecture: Utilizes Gorilla Mux for routing and Redis for efficient data storage.
- Scalable and Maintainable: Structured for scalability and easy maintenance, ensuring smooth operation even with high volumes of requests.
- Main_test.go file included
- Detailed documentation, describing testing and demonstration of microservice usage.

[Explore the URL Shortener Microservice on GitHub](https://github.com/amy324/Go-URL-Shortener-Microservice)

This project demonstrates expertise in backend development and provides a practical solution for managing lengthy URLs effectively.

### Fake Payment Gateway Microservice
**Tech: PostgreSQL, Encoding/json, net/http, Goluhn, Gorilla/Mux, Lib/pq, validation**

The Fake Payment Gateway Microservice is a demonstration of card validation through a simple payment gateway, implemented in Golang. It allows users to submit payment information, including name, card number, payment amount, and currency, via HTTP requests. The server validates the credit card number using the Luhn algorithm and inserts the payment information into a PostgreSQL database. Clients can also retrieve invoice details using the payment ID.

**Key Features**:
- Card Validation: Utilizes the Luhn algorithm to validate credit card numbers.
- Database Integration: Inserts payment information into a PostgreSQL database.
- HTTP Endpoints: Provides endpoints for submitting payment information and retrieving invoice details.
- Demonstrative Purposes: Intended for learning and demonstration, not for genuine payment processing.

[Explore the Fake Payment Gateway Microservice on GitHub](https://github.com/amy324/Fake-Payment-Gateway-Microservice)

This project showcases fundamental card validation concepts and backend development skills, providing insight into payment gateway implementation.



### Monte Carlo Pi Simulator
**Tech: Concurrency, Modular Structure, Gonum/Plot**

A CLI application performing a Monte Carlo simulation to estimate the value of π, utilizing Golang's concurrency features and plotting libraries for efficient computation and data visualization.

**Key Features**:
- Golang Concurrency: Efficient generation and processing of random points concurrently.
- Modular Structure: Organized for readability and maintainability.
- Plotting with Gonum/Plot: Visualization of generated points for analysis. Saves scatter graph as a .png file to folder directory.

[View Monte Carlo Pi Simulator on GitHub](https://github.com/amy324/Golang-Monte-Carlo-Simulator)

### CSV Parsing CLI Tool
**Tech: PostgreSQL, Lib/pq, Encoding/csv, os, Cobra, strconv**

A CLI tool for parsing CSV data, saving to PostgreSQL, and performing calculations with said data. Prioritizes efficiency, scalability, and maintainability within the backend infrastructure.

**Key Features**:
- CSV Data Parsing: Streamline the parsing of CSV files effortlessly with the `parsecsv` command.
- PostgreSQL Integration: Establish seamless connections to a PostgreSQL database through the `connectdb` command.
- Foundations for Advanced Analytics: Establish a solid groundwork for tackling advanced statistical analysis tasks, showcasing a backend-centric approach.

[CSV Parsing CLI Tool](https://github.com/amy324/CLI-CSV-Parsing-Tool)

### Classic Computer Science Problems Series

Implementations of classic problems using Goroutines and Go concurrency features.

**Projects**:
- [**Dijkstra's Algorithm for Shortest Paths**](https://github.com/amy324/Golang-Algorithm-for-Shortest-Paths)
     * **Tech: initialize the graph, add edges, and calculate shortest paths from a specified source vertex**
- [**Sleeping Barber Problem**](https://github.com/amy324/Golang-Sleeping-Barber-Problem)
     * **Tech: Concurrency, Pointers, Goroutines, Channels, Randomized, Time-Based.**
- [**Dining Philosophers Problem**](https://github.com/amy324/Dining-Philosophers-Problem)
     * **Tech: Concurrency, Goroutines, Mutexes, Synchronization, Algorithm, testing**
- [**Producer-Consumer Problem**](https://github.com/amy324/Goroutine-Producer-Consumer-Problem)
     * **Tech: Concurrency, Goroutines, Pointers, Syncronization, Buffer**

### CLI To-Do List App
**Tech: CRUD (Create, Read, Update, Delete) operations, bufio, os, strconv**

Demonstrates implementing CRUD funbctionality with Golang.

**Key Features**:
- Add, View, Mark, and Delete Tasks: Basic task management functionalities.
- Simple Command-Line Interface: Easy-to-use interface for task management.

[Check out the CLI To-Do List App](https://github.com/amy324/Golang-Todo-List-CLI-App)

### Golang Weather CLI App
**Tech: Data structures, JSON response, API calls, encoding/json, flag, io, net/http, net/url**

A command-line tool fetching and displaying weather information for a given location. Demonstrates retrieving data from a web API using Golang CLI

**Features**:
- Retrieve Current Weather: Based on location, supports automatic detection or manual entry.
- User-friendly Interface: Simple CLI interface for quick weather checks.

[Explore Golang Weather CLI App](https://github.com/amy324/Golang-CLI-Weather-App)

### Golang RESTful API Demo
**Tech: RESTful API, encoding/json, net/http, Gorilla/Mux**

A simple backend that demonstrates creating RESTful API endpoints in Golang. The purpose of the API can be anything, but for this, I chose to make its purpose for submitting data points and retrieving analysis results.

[Golang RESTful API Demo](https://github.com/amy324/RESTful-API-Demo-Golang)












