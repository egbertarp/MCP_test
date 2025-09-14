# MCP Test Spring Boot Application

A basic Spring Boot application created as a test project.

## Features

- REST API endpoints
- Health check endpoint
- Basic web controller

## Endpoints

- `GET /` - Welcome message
- `GET /hello?name=YourName` - Personalized greeting
- `GET /health` - Health check

## Running the Application

### Prerequisites
- Java 17 or higher
- Maven 3.6 or higher

### Build and Run

```bash
# Build the application
mvn clean package

# Run the application
mvn spring-boot:run
```

Or run the JAR file directly:

```bash
java -jar target/mcp-test-0.0.1-SNAPSHOT.jar
```

The application will start on port 8080. You can access it at `http://localhost:8080`.

## Testing

Run tests with:

```bash
mvn test
```

## Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com/example/mcptest/
│   │       ├── McpTestApplication.java
│   │       └── controller/
│   │           └── HelloController.java
│   └── resources/
│       └── application.properties
└── test/
    └── java/
        └── com/example/mcptest/
            └── McpTestApplicationTests.java
```
