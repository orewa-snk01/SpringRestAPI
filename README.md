# API with Spring Boot :seedling:

My first attempt at using __Spring Boot__. Features an __API__ with __CRUD__ operations (Get, Post, Put, Delete).
Mimics linking to database system and could be easily linked to one.

## Installation

**1. Clone the application**

```bash
https://github.com/
```

**2. Build and run the app using maven**

```bash
mvn package
java -jar target/demo-0.0.1-SNAPSHOT.jar
```

Alternatively, you can run the app using

```bash
mvn spring-boot:run
```

The app will start running at <http://localhost:8080>.

## Explore APIs

The app defines following CRUD APIs.

    GET /api/v1/person

    POST /api/v1/person

    GET /api/v1/person/{userId}

    PUT /api/v1/person/{userId}

    DELETE /api/v1/person/{userId}

POST Body example

    {
      "name" : "Joe Exotic"
    }
