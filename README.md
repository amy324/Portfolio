# Portfolio

Hiy! Welcome to my portfolio.

My GitHub is where I keep projects I've built outside of work, everything from larger apps to small, focused microservices that each demonstrate a specific skill. Most of it is written in Go because I like that it compiles straight to machine code and how efficient it is.

Every project has  documentation showing how it works, why I made certain decisions, and how to run it yourself. I try to stick to open source tools wherever possible, so anything here can be customised if you want to build on it. Note: this is my personal account, so it doesn't include client or employer work..

Each public project on my profile has been specially crafted to serve as portfolio pieces. Please note, this is my personal account and does not include any of my professional projects, as these remain confidential. 

[Explore my GitHub profile](https://github.com/amy324)

## Contents

Click to view the summary of a specific project, or keep scrolling to see all:

### Larger Projects

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

## Larger Projects

### Ticket Raising Platform Backend
**Tech: Gorilla/Mux, MySQl, JSON Web Tokens, bcrypt, Render, Mailtrap, net/http, validation, authentication, RESTful APIs, CRUD operations**

A full backend for a support ticket system built around Go's standard net/http, with a MySQL database behind it.

**Key Features**:
- JWT-based authentication and authorisation
- Full CRUD on tickets, with categorisation and tracking
- In-thread messaging on tickets
- Email notifications on ticket updates (tested via Mailtrap)
  
[Explore Ticket Raising Platform Backend](https://github.com/amy324/Ticket-Raising-Platform-Backend)

### Steam Games Data CLI App
**Tech: Web Scraping, Goquery, Cobra, Encoding, JSON parsing, CSV parsing, regex, os/exec, bufio, bytes, net/http**

A CLI that scrapes game data straight from the Steam store — titles, prices, release dates, reviews, tags, developers, publishers, system requirements.

**Key Features**:
- Exports scraped data to both JSON and CSV
- Search by keyword from the command line
- Pull deep-dive details (description, dev, publisher, requirements) for a specific game by link
- Built with Steam's Data Terms of Use in mind

[Explore Steam Games Data CLI App](https://github.com/amy324/Steam-Games-Data-CLI-App)

## Blogging Platform Infastructure
**Tech: IaC, Terraform, HCL, Prometheus, Docker, Golang, Gin, ORM, PostgreSQL**

An SRE-focused infrastructure project built to demonstrate reliability, automated provisioning, and observability.

**Key Features**:
- Dockerized components, orchestrated and provisioned via Terraform (IaC)
- Prometheus monitoring for real-time metrics and alerting on KPIs/SLOs
- Container health checks and automatic restarts for resilience
- Built to scale horizontally (Docker Swarm/Kubernetes-ready)

[Check Out The Project Here](https://github.com/amy324/Blogging-Platform-Infrastructure)

### Advanced Data Analysis CLI Framework
**Tech: MySQL, Cobra, Python, Python, pandas, sklearn, os/ex**

A hybrid CLI tool built for customisable data analysis pipelines. Modelled after a production tool developed for a customer project.

**Key Features**:
- Modular structure so it's easy to extend
- Connects to MySQL for storing/retrieving results
- Plug in your own Python or Go scripts for custom analysis
- Contains a working example: logistic regression on CSV data via scikit-learn

[Explore Advanced Data Analysis CLI Framework](https://github.com/amy324/CLI-Framework-for-Advanced-Analysis)

## Demonstrative Projects/Microservices 

### Port Scanner
**Tech: Python, Socket Programming, CLI, TCP, IP Address Scanning, Network Troubleshooting, Monitoring, Networking Protocols, Date and Time Handling, ASCII Artt**

Scans a target IP across the full port range (1–65535) for network troubleshooting and basic security auditing. Includes timestamped output and ASCII art banners via pyfiglet.

[Explore the Port Scanner on GitHub](https://github.com/amy324/Port-Scanner)

### CI-CD Pipeline Automation Tool
**CI/CD Pipeline Automation, Cobra, yaml, Go-Git.**

A CLI tool for automating CI/CD on Go projects. Configure the repository URL, branch, and test command, and it handles fetching source code, running tests, and deploying.

[View the Project here](https://github.com/amy324/CI-CD-Pipeline-Automation-Tool)

### Concurrent Task Scheduler
**Tech: Concurrency, Pointers, Goroutines, Mutexes, Logrus, sync, testing.**

Runs multiple tasks concurrently while limiting how many execute at once, to manage resource usage. Structured logging via Logrus provides visibility into task execution.

[Check out the Concurrent Task Scheduler here](https://github.com/amy324/Concurrent-Task-Scheduler)


### Markdown to HTML Microservice
**Tech: Regex**

Converts Markdown to HTML using regular expressions — handles headings, bold/italic text, lists, links, and images. Includes a sample input in main.go for testing.

[Click here for the Markdown to HTML Microservice](https://github.com/amy324/Markdown-To-HTML-Microservice.git)

### URL Shortener Microservice
**Tech: Redis, Gorilla/Mux, Godotenv, Encoding/JSON, net/http, os, Render, httptest, testing, APIs**
Shortens URLs and redirects to the original destination. Uses Gorilla Mux for routing and Redis for fast storage and retrieval. Structured for scalability, with a full test suite (main_test.go) and detailed documentation.

[Explore the URL Shortener Microservice on GitHub](https://github.com/amy324/Go-URL-Shortener-Microservice)

This project demonstrates expertise in backend development and provides a practical solution for managing lengthy URLs effectively.

### Fake Payment Gateway Microservice
**Tech: PostgreSQL, Encoding/json, net/http, Goluhn, Gorilla/Mux, Lib/pq, validation**

A demonstration payment gateway, not intended for real transactions.

- Validates card numbers using the Luhn algorithm
- Stores payment information in PostgreSQL
-  Endpoints for submitting payments and retrieving invoices by ID

[Explore the Fake Payment Gateway Microservice on GitHub](https://github.com/amy324/Fake-Payment-Gateway-Microservice)


### Monte Carlo Pi Simulator
**Tech: Concurrency, Modular Structure, Gonum/Plot**

Estimates π via Monte Carlo simulation, generating and processing random points concurrently, then plots the results as a scatter graph saved to PNG.

[View Monte Carlo Pi Simulator on GitHub](https://github.com/amy324/Golang-Monte-Carlo-Simulator)

### CSV Parsing CLI Tool
**Tech: PostgreSQL, Lib/pq, Encoding/csv, os, Cobra, strconv**

Parses CSV files, saves the data to PostgreSQL via a connectdb command, and performs calculations.

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

A basic task manager supporting add, view, complete, and delete operations — a clean CRUD implementation in Go.

[Check out the CLI To-Do List App](https://github.com/amy324/Golang-Todo-List-CLI-App)

### Golang Weather CLI App
**Tech: Data structures, JSON response, API calls, encoding/json, flag, io, net/http, net/url**

Fetches current weather for a given location, with support for automatic detection or manual entry, through a simple CLI.

[Explore Golang Weather CLI App](https://github.com/amy324/Golang-CLI-Weather-App)

### Golang RESTful API Demo
**Tech: RESTful API, encoding/json, net/http, Gorilla/Mux**

A minimal REST API demonstrating endpoint design in Go — includes endpoints for submitting data points and retrieving analysis results.

[Golang RESTful API Demo](https://github.com/amy324/RESTful-API-Demo-Golang)












