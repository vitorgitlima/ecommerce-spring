# E-commerce Spring Backend

This project is built with Spring Boot and requires Java 17, Maven, and Docker to run.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Java 17](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [Maven](https://maven.apache.org/)
- [Docker](https://www.docker.com/)

## Getting Started

1. **Clone the repository:**
   \```sh
   git clone https://github.com/vitorgitlima/ecommerce-spring
   cd ecommerce-spring
   \```

2. **Navigate to the Docker directory:**
   \```sh
   cd infra/docker
   \```

3. **Run the Docker Compose command:**
   \```sh
   docker compose up -d
   \```

   This command will start all the necessary services defined in the Docker Compose file.

## API Endpoints

The API exposes the following endpoints:

- **Countries:** `http://localhost:8080/api/countries{?page,size,sort}`
- **States:** `http://localhost:8080/api/states{?page,size,sort}`
- **Products:** `http://localhost:8080/api/products{?page,size,sort}`
- **Product Categories:** `http://localhost:8080/api/product-category{?page,size,sort}`
- **Profile:** `http://localhost:8080/api/profile`

Each endpoint supports pagination and sorting through query parameters (`page`, `size`, `sort`).

## Further Information
Contact

