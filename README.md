JWTDemo — JWT (JSON Web Token) Authentication using Entity Framework Core:

This project demonstrates how to implement JWT-based authentication in a .NET Core API using Entity Framework Core. It’s designed for developers who want to understand and build real-world authentication logic used in modern backend applications.

📂 Project Structure Overview

🔹 Controllers

AuthController: Handles API routes related to user authentication.

Includes logic to restrict API access using [Authorize] attributes and token validation.

🔹 DTOs (Data Transfer Objects)

Contains models such as UserLoginDto to accept username and password input for authentication.

🔹 JWT Repository

Implements a method to generate JWT tokens using a secret key from the configuration.

Encodes claims and signing credentials securely.

🔹 AppSettings.json

Stores configuration values like the JWT secret key, issuer, and audience used during token generation and validation.

🚀 Features

Secure token-based authentication.

Configurable secret key and expiration time.

Follows clean, modular architecture (Controller → Service → Repository).
