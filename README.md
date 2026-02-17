# Customer Management PAPI

## Overview

Customer API Integration is a MuleSoft application that exposes REST APIs for managing customer data.  
The project follows API-led connectivity principles and is designed for enterprise deployment.

---

## Tech Stack

- Mule Runtime 4
- Java 17
- Maven
- MUnit
- Anypoint Platform

---

## Project Structure

```
src/main/mule/          
src/main/resources/     
src/test/munit/        
pom.xml              
```

---

## API Endpoints

### Get Customers
```
GET /api/customers
```

### Create Customer
```
POST /api/customers
```

---

## Run Locally

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Open in Anypoint Studio.

3. Run as:
   ```
   Mule Application
   ```

Default endpoint:
```
http://localhost:8081/api/customers
```

---

## Testing

Run MUnit tests:

```
mvn clean test
```

---

## Branching Strategy

- `main` → Production-ready code  
- `feature/*` → Feature development  
- `hotfix/*` → Production fixes  

Pull Requests are required before merging into `main`.

---

## Versioning

This project follows Semantic Versioning:

```
MAJOR.MINOR.PATCH
```

Example:
```
v1.0.0
```

---

## Maintainers

Integration Team
