

# Portfolio

Hi! Welcome to my personal portfolio.

My professional work involves large-scale infrastructure and production systems, but those projects and environments remain confidential and aren't represented here. Instead, this portfolio contains a collection of fun little projects I've built outside of my professional work.

These projects are deliberately quick and kept small and focused. They demonstrate particular technologies and coding concepts without turning each idea into a full-scale application.

Most are written in Go, which I particularly enjoy for systems programming, concurrency and building efficient, self-contained tools.

Every public project includes documentation covering how it works, relevant design decisions and how to run it yourself.
**[Explore my GitHub profile](https://github.com/amy324)**

## Contents

Click a project to view its summary, or keep scrolling to see them all.

| Project                                                                           | Technologies                                   |
| --------------------------------------------------------------------------------- | ---------------------------------------------- |
| **[Ticket Raising Platform Backend](#ticket-raising-platform-backend)**           | Go, MySQL, REST APIs, JWT, bcrypt, Gorilla/Mux |
| **[Steam Games Data CLI App](#steam-games-data-cli-app)**                         | Go, Web Scraping, Cobra, JSON, CSV, regex      |
| **[Blogging Platform Infrastructure](#blogging-platform-infrastructure)**         | Terraform, Docker, Prometheus, Go, PostgreSQL  |
| **[Advanced Data Analysis CLI Framework](#advanced-data-analysis-cli-framework)** | Go, Python, MySQL, Cobra, pandas, scikit-learn |
| **[CI/CD Pipeline Automation Tool](#cicd-pipeline-automation-tool)**             | Go, Cobra, YAML, Go-Git                        |
| **[Concurrent Task Scheduler](#concurrent-task-scheduler)**                       | Go, Goroutines, Mutexes, Concurrency, Testing  |
| **[URL Shortener Microservice](#url-shortener-microservice)**                     | Go, Redis, Gorilla/Mux, REST APIs, Testing     |
| **[Fake Payment Gateway Microservice](#fake-payment-gateway-microservice)**       | Go, PostgreSQL, REST APIs, Validation          |
| **[Port Scanner](#port-scanner)**                                                 | Python, Socket Programming, TCP/IP, CLI        |
| **[Markdown to HTML Microservice](#markdown-to-html-microservice)**               | Go, Regex                                      |

## Projects

### Ticket Raising Platform Backend

**Tech: Go, MySQL, REST APIs, JWT, bcrypt, Gorilla/Mux, Render, Mailtrap**

A backend for a support ticket system, built with Go's standard `net/http` package and a MySQL database.

**Key features:**

* JWT-based authentication and authorisation
* CRUD operations for tickets, including categorisation and tracking
* In-thread ticket messaging
* Email notifications for ticket updates

[Explore Ticket Raising Platform Backend](https://github.com/amy324/Ticket-Raising-Platform-Backend)

### Steam Games Data CLI App

**Tech: Go, Web Scraping, Goquery, Cobra, JSON, CSV, regex**

A command-line tool that collects game data from the Steam store, including titles, prices, release dates, reviews, tags, developers and system requirements.

**Key features:**

* Exports data to JSON and CSV
* Keyword searching from the command line
* Retrieves detailed information for individual games
* Designed with Steam's Data Terms of Use in mind

[Explore Steam Games Data CLI App](https://github.com/amy324/Steam-Games-Data-CLI-App)

### Blogging Platform Infrastructure

**Tech: Terraform, Docker, Prometheus, Go, Gin, PostgreSQL**

An infrastructure-focused project demonstrating automated provisioning, containerisation and observability around a small blogging platform.

**Key features:**

* Infrastructure provisioned with Terraform
* Containerised application components
* Prometheus monitoring and alerting
* Health checks and automatic container recovery
* Designed with horizontal scaling in mind

[Explore Blogging Platform Infrastructure](https://github.com/amy324/Blogging-Platform-Infrastructure)

### Advanced Data Analysis CLI Framework

**Tech: Go, Python, MySQL, Cobra, pandas, scikit-learn**

A command-line framework designed to **let users run and extend their own data analysis workflows**. It was inspired by a production-style analysis tool and provides the framework around which individual analyses can be run.

**Key features:**

* Modular structure for adding custom analysis scripts
* MySQL integration for storing and retrieving results
* Supports user-provided Python or Go analysis scripts
* Includes a sample logistic regression analysis using scikit-learn

[Explore Advanced Data Analysis CLI Framework](https://github.com/amy324/CLI-Framework-for-Advanced-Analysis)

### CI/CD Pipeline Automation Tool

**Tech: Go, Cobra, YAML, Go-Git**

A CLI tool for automating a CI/CD workflow for Go projects. It takes a repository, branch and test command as configuration and handles fetching the code, running tests and deploying.

[Explore CI/CD Pipeline Automation Tool](https://github.com/amy324/CI-CD-Pipeline-Automation-Tool)

### Concurrent Task Scheduler

**Tech: Go, Goroutines, Mutexes, Logrus, Testing**

A scheduler that runs tasks concurrently while limiting the number running at once.

Uses structured logging to provide visibility into task execution.

[Explore Concurrent Task Scheduler](https://github.com/amy324/Concurrent-Task-Scheduler)

### URL Shortener Microservice

**Tech: Go, Redis, Gorilla/Mux, REST APIs, Testing**

A URL shortening service that stores shortened URLs in Redis and redirects requests to their original destinations.

Includes a test suite and documentation covering the API and implementation.

[Explore URL Shortener Microservice](https://github.com/amy324/Go-URL-Shortener-Microservice)

### Fake Payment Gateway Microservice

**Tech: Go, PostgreSQL, REST APIs, Validation**

A demonstration payment gateway for development and testing rather than real transactions.

* Validates card numbers using the Luhn algorithm
* Stores payment information in PostgreSQL
* Provides endpoints for submitting payments and retrieving invoices

[Explore Fake Payment Gateway Microservice](https://github.com/amy324/Fake-Payment-Gateway-Microservice)

### Port Scanner

**Tech: Python, Socket Programming, TCP/IP, CLI**

A CLI port scanner that checks ports 1–65535 on a target IP address.

Includes timestamped output and a small ASCII banner.

[Explore Port Scanner](https://github.com/amy324/Port-Scanner)

### Markdown to HTML Microservice

**Tech: Go, Regex**

A microservice that converts basic Markdown into HTML using regular expressions, including headings, formatting, lists, links and images.

[Explore Markdown to HTML Microservice](https://github.com/amy324/Markdown-To-HTML-Microservice)











