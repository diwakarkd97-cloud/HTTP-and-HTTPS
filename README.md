# HTTP vs HTTPS vs HttpMethod

# 🌐 HTTP (HyperText Transfer Protocol)

HTTP is a **network communication protocol** used to transfer data between a client and a server.

It defines the rules for how requests and responses are exchanged over the internet.

## Key Features

- Default Port: **80**
- Not secure
- Data is transferred in plain text
- No encryption mechanism
- Used for communication between browsers, servers, and APIs
- Supports versions:
  - HTTP/1.0
  - HTTP/1.1
  - HTTP/2
  - HTTP/3

### Example

```
http://example.com
```

### Real-World Analogy

HTTP is like sending a **postcard**. Anyone who intercepts it can read the information.

---

# 🔒 HTTPS (HyperText Transfer Protocol Secure)

HTTPS is the **secure version of HTTP**.

It uses **SSL/TLS encryption** to protect communication between the client and server.

## Key Features

- Default Port: **443**
- Secure communication
- Encrypts transmitted data
- Uses SSL/TLS certificates
- Provides:
  - Data confidentiality
  - Authentication
  - Data integrity

## Used In

- Online banking
- Shopping websites
- Payment gateways
- Login pages
- Secure applications

### Example

```
https://example.com
```

### Real-World Analogy

HTTPS is like sending a **sealed letter**, where only the sender and receiver can read the content.

---

# ⚙️ HttpMethod

HttpMethod represents the **HTTP request methods used in programming**.

It defines what action should be performed on a resource while communicating through HTTP or HTTPS.

## Common HTTP Methods

| Method | Purpose |
|--------|---------|
| GET | Retrieve data from server |
| POST | Create new data |
| PUT | Update existing data |
| DELETE | Delete data |
| PATCH | Partially update data |

## Example (Spring Boot / Java)

```java
HttpMethod.GET

HttpMethod.POST

HttpMethod.PUT

HttpMethod.DELETE
```

## Used In

- Java
- Spring Boot
- Node.js
- .NET
- Python Web Frameworks

---

# 🔍 HTTP vs HTTPS vs HttpMethod Comparison

| Feature | HTTP | HTTPS | HttpMethod |
|---------|------|-------|------------|
| Full Form | HyperText Transfer Protocol | HyperText Transfer Protocol Secure | HTTP Request Methods |
| Type | Network Protocol | Secure Network Protocol | Programming Concept |
| Purpose | Transfer data between client and server | Securely transfer data | Define request operation |
| Security | Not Secure | Secure | No security role |
| Encryption | No Encryption | SSL/TLS Encryption | Not Applicable |
| Default Port | 80 | 443 | No Port |
| Example | http://example.com | https://example.com | HttpMethod.GET |
| Used By | Websites, APIs | Banking, Shopping, Secure Websites | Java, Spring Boot, Node.js |

---

