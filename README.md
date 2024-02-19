# Portfolio

I hold a Master of Research degree in statistics, bringing a solid foundation in advanced statistical theory to the world of engineering. With a passion for both mathematics and programming, I thoroughly enjoy demonstrating how statistical techniques and a deep understanding of mathematical theory can be leveraged in software engineering to solve challenges and develop resilient, scalable applications.  

🔗 My GitHub serves as a curated showcase of projects, ranging from professional-level examples to smaller projects that act as microservices or are demonstrative of specific skills and highlight the versatility of Golang.

Each public project on my profile has been specially crafted to serve as portfolio pieces. Please note, my professional work for clients is set to private as these remain confidential.

[Explore my GitHub profile](https://github.com/amy324)

## Large-Scale Examples

### Ticket Raising Platform Backend
A comprehensive backend system demonstrating best practices in Golang development, including user authentication, ticket management, real-time communication, and email notifications.

**Key Features**:
- User Authentication and Authorization: Token-based authentication and authorization mechanisms using JSON Web Tokens (JWT).
- Ticket Management: Endpoints for CRUD operations on support tickets, categorized and tracked efficiently.
- Real-Time Communication: Messaging features embedded within ticket threads.
- Email Notifications: Notifies users about ticket updates and relevant events, utilizing Mailtrap for testing purposes.
- Data Persistence and Management: Utilizes MySQL for storing and managing data.
- **Tech Stack**: Golang, Gorilla Mux, MySQL, Mailtrap, JWT for authentication, Render for deployment, Postman for testing, Git for version control.

[Explore Ticket Raising Platform Backend](https://github.com/amy324/Ticket-Raising-Platform-Backend)

### Advanced Data Analysis CLI Framework
A versatile and scalable framework tailored for conducting fully customizable sophisticated data analysis tasks through a command-line interface. Its design and functionality closely resemble a custom program I developed for a client, showcasing its adaptability and effectiveness in real-world scenarios.

**Key Features**:
- Modular Structure: Scalable and maintainable with distinct modules.
- Database Interaction: Seamless connection to MySQL databases for storing and retrieving results.
- Customizable Analysis & Python Script Integration: Users can run custom scripts, integrating Python or Golang commands.
- Command-Line Interface: Utilizes Cobra library for user-friendly interactions.
- **Tech Stack**: Golang, Python integration, MySQL for database, Git for version control.

[Explore Advanced Data Analysis CLI Framework](https://github.com/amy324/CLI-Framework-for-Advanced-Analysis)

## Demonstrative Projects/Microservices 

### Markdown to HTML Microservice
This is a microservice written in Golang that converts Markdown syntax to HTML. It provides a function `MarkdownToHTML` that takes Markdown content as input and returns the corresponding HTML content. The `main.go` file contains the logic for converting Markdown to HTML. It defines the `MarkdownToHTML` function, which takes Markdown content as input and uses regular expressions to identify and replace Markdown syntax with corresponding HTML tags. This includes handling headings, bold and italic text, unordered and ordered lists, links, and images.
Includes an example Markdown in `func main` - feel free to replace with any Markdown text to convert to HTML. Documentation provides expected terminal output.

[Click here for the Markdown to HTML Microservice](https://github.com/amy324/Markdown-To-HTML-Microservice.git)

### URL Shortener Microservice

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

The Fake Payment Gateway Microservice is a demonstration of card validation through a simple payment gateway, implemented in Golang. It allows users to submit payment information, including name, card number, payment amount, and currency, via HTTP requests. The server validates the credit card number using the Luhn algorithm and inserts the payment information into a PostgreSQL database. Clients can also retrieve invoice details using the payment ID.

**Key Features**:
- Card Validation: Utilizes the Luhn algorithm to validate credit card numbers.
- Database Integration: Inserts payment information into a PostgreSQL database.
- HTTP Endpoints: Provides endpoints for submitting payment information and retrieving invoice details.
- Demonstrative Purposes: Intended for learning and demonstration, not for genuine payment processing.

[Explore the Fake Payment Gateway Microservice on GitHub](https://github.com/amy324/Fake-Payment-Gateway-Microservice)

This project showcases fundamental card validation concepts and backend development skills, providing insight into payment gateway implementation.


### Monte Carlo Pi Simulator
A CLI application performing a Monte Carlo simulation to estimate the value of π, utilizing Golang's concurrency features and plotting libraries for efficient computation and data visualization.

**Key Features**:
- Golang Concurrency: Efficient generation and processing of random points concurrently.
- Modular Structure: Organized for readability and maintainability.
- Plotting with Gonum/Plot: Visualization of generated points for analysis. Saves scatter graph as a .png file to folder directory.

[View Monte Carlo Pi Simulator on GitHub](https://github.com/amy324/Golang-Monte-Carlo-Simulator)

### CSV Parsing CLI Tool
A CLI tool for parsing CSV data, saving to PostgreSQL, and performing calculations with said data. Prioritizes efficiency, scalability, and maintainability within the backend infrastructure.

**Features**:
- CSV Data Parsing: Streamline the parsing of CSV files effortlessly with the `parsecsv` command.
- PostgreSQL Integration: Establish seamless connections to a PostgreSQL database through the `connectdb` command.
- Foundations for Advanced Analytics: Establish a solid groundwork for tackling advanced statistical analysis tasks, showcasing a backend-centric approach.

[CSV Parsing CLI Tool](https://github.com/amy324/CLI-CSV-Parsing-Tool)

### Classic Computer Science Problems Series
Implementations of classic problems using Goroutines and Go concurrency features.

**Projects**:
- [**Dijkstra's Algorithm for Shortest Paths**](https://github.com/amy324/Golang-Algorithm-for-Shortest-Paths)
- [**Sleeping Barber Problem**](https://github.com/amy324/Golang-Sleeping-Barber-Problem)
- [**Dining Philosophers Problem**](https://github.com/amy324/Dining-Philosophers-Problem)
- [**Producer-Consumer Problem**](https://github.com/amy324/Goroutine-Producer-Consumer-Problem)

### CLI To-Do List App
Demonstrates implementing CRUD funbctionality with Golang.

**Features**:
- Add, View, Mark, and Delete Tasks: Basic task management functionalities.
- Simple Command-Line Interface: Easy-to-use interface for task management.

[Check out the CLI To-Do List App](https://github.com/amy324/Golang-Todo-List-CLI-App)

### Golang Weather CLI App
A command-line tool fetching and displaying weather information for a given location. Demonstrates retrieving data from a web API using Golang CLI

**Features**:
- Retrieve Current Weather: Based on location, supports automatic detection or manual entry.
- User-friendly Interface: Simple CLI interface for quick weather checks.

[Explore Golang Weather CLI App](https://github.com/amy324/Golang-CLI-Weather-App)

### Golang RESTful API Demo
A simple backend that demonstrates creating RESTful API endpoints in Golang. The purpose of the API can be anything, but for this, I chose to make its purpose for submitting data points and retrieving analysis results.

[Golang RESTful API Demo](https://github.com/amy324/RESTful-API-Demo-Golang)












