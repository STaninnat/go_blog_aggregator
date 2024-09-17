# Blog Aggregator Microservice

Golang Web Server and RSS Scraper

This project is a blog aggregator microservice built in Go. It involves creating a RESTful API and integrating it with a long-running service worker to fetch and process data from remote blogs over the internet. The project leverages production-ready tools like PostgreSQL, SQLc, Goose, and pgAdmin to manage the database.

## Features

- **RESTful API**: Build and expose endpoints to interact with the aggregator service.
- **Long-Running Service Worker**: A service worker that continuously fetches blog data from remote locations.
- **Database Integration**: Using PostgreSQL for database management with SQLc for SQL code generation and Goose for database migrations.
- **Web Scraping**: Fetch blog content from external sites.

## Tools Used

- **Go**: The primary language for building the microservice.
- **PostgreSQL**: Relational database used to store aggregated blog data.
- **SQLc**: Automatically generates Go code from SQL queries.
- **Goose**: Manages database migrations.
- **pgAdmin**: Database management tool to interact with PostgreSQL.

## Installation

1. Clone the repository.
2. Set up PostgreSQL and configure your environment variables.
3. Run the necessary database migrations with Goose.
4. Start the service worker and API using Go. ```go build -o go_blog_aggregator && ./go_blog_aggregator```

## Future Enhancements

- Add authentication and authorization for API access.
- Implement more sophisticated data-fetching and caching mechanisms.
- Provide an admin panel for monitoring the service worker's activity.