## Features

### Major Frameworks & Technologies

- Spring Boot 2.7.x (latest version)
- Spring MVC
- MyBatis + MyBatis Plus for data access (with pagination support)
- Spring Boot DevTools and Project Processor
- Spring AOP for aspect-oriented programming
- Spring Scheduler for scheduled tasks
- Spring Transaction Management (annotations)

### Data Storage

- MySQL relational database
- Redis in-memory database
- Elasticsearch search engine
- Tencent Cloud COS for object storage

### Utility Libraries

- EasyExcel for Excel file handling
- Hutool utility toolkit
- Gson for JSON parsing
- Apache Commons Lang3 utilities
- Lombok annotations for reducing boilerplate code

### Business Features

- Distributed login session management via Spring Session Redis
- Global request and response interceptors (for logging)
- Global exception handling
- Custom error codes
- Common response wrapper class
- Swagger + Knife4j for API documentation
- Custom permission annotations + global validation
- Global CORS handling
- Solution for long integer precision loss
- Multi-environment configuration support

## Business Functionalities

- Sample SQL scripts for users, posts, likes, and favorites tables
- User authentication (login, registration, logout, update, retrieval, role management)
- Post management (create, delete, edit, update, database search, Elasticsearch flexible search)
- Post likes and unlikes
- Post favorites, unfavorites, and retrieval of favorited posts
- Full and incremental synchronization of posts from database to Elasticsearch (scheduled tasks)
- Support for WeChat Open Platform login
- Support for WeChat official account subscription, message receiving/sending, and custom menu setup
- File upload services for multiple business modules

### Unit Testing

- JUnit5 unit testing
- Sample unit test classes included

### Architecture

- Well-organized layered structure

## Quick Start

> All parts requiring modification are marked with `todo` comments in the code for easy reference.

### MySQL Configuration

1. Update your `application.yml` with your own database connection:

```yaml
spring:
  datasource:
    driver-class-name: com.mysql.cj.jdbc.Driver
    url: jdbc:mysql://localhost:3306/my_db
    username: root
    password: 123456



