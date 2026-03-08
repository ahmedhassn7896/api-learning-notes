# API Learning Roadmap

A structured guide to the most important APIs and communication technologies used in modern backend systems, data engineering platforms, and distributed architectures.

---

# 1. HTTP APIs (Foundational)

These are the most common APIs used on the web.

## REST API

The most widely used architecture for web services.

Concepts to learn:

* HTTP Methods (GET, POST, PUT, PATCH, DELETE)
* Status Codes
* Authentication
* Pagination
* Rate Limiting

Resources:
https://restfulapi.net/

---

## GraphQL API

An alternative to REST that allows clients to request only the data they need.

Topics:

* Queries
* Mutations
* Schemas
* Resolvers

Documentation:
https://graphql.org/learn/

---

# 2. High Performance APIs

## gRPC

High-performance communication protocol for microservices.

Based on:
Protocol Buffers

Concepts:

* Unary RPC
* Streaming RPC
* Service definitions

Documentation:
https://grpc.io/docs/

---

# 3. Real-Time APIs

## WebSocket API

Used for real-time communication.

Use cases:

* chat applications
* live dashboards
* trading platforms

Learn:

* WebSocket protocol
* pub/sub systems

Resource:
https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API

---

# 4. Streaming APIs

## Apache Kafka APIs

Important for event-driven architectures and data engineering systems.

APIs to learn:

* Producer API
* Consumer API
* Streams API
* Admin API

Documentation:
https://kafka.apache.org/documentation/

---

# 5. Authentication APIs

## OAuth2

Industry standard for authorization.

Used by platforms like Google and Microsoft.

Learn:

* Authorization Code Flow
* Access Tokens
* Refresh Tokens

Resource:
https://oauth.net/2/

---

## JWT

JSON Web Token authentication method.

Concepts:

* token generation
* token validation
* token expiration

Resource:
https://jwt.io/introduction

---

# 6. Cloud APIs

Modern applications interact heavily with cloud APIs.

Important ones:

## AWS APIs

Examples:

* S3 API
* Lambda API
* Kinesis API

Documentation:
https://docs.aws.amazon.com/

---

# 7. Data Platform APIs

Used in data engineering pipelines.

Important technologies:

Apache Spark API
Apache Airflow API
Elasticsearch API

Documentation:
https://spark.apache.org/docs/latest/api.html

---

# 8. Database APIs

APIs used to interact with databases.

Examples:

SQL Drivers
ORM frameworks

Tools:

SQLAlchemy
Prisma

---

# 9. Monitoring APIs

Used for observability and system monitoring.

Examples:

Prometheus API
Grafana API

Resources:
https://prometheus.io/docs/prometheus/latest/querying/api/

---

# Recommended Learning Order

1. REST API
2. Authentication (JWT / OAuth2)
3. WebSocket
4. GraphQL
5. gRPC
6. Kafka APIs
7. Cloud APIs
8. Monitoring APIs

---

# Advice

Do not try to memorize APIs.

Instead:

* Build real projects
* Design scalable APIs
* Work with distributed systems

APIs are tools, not the goal.
