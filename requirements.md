# Backend Feature Requirements – Airbnb Clone

## 1. User Authentication

### Objective:
Allow users to securely register, log in, and maintain a session via JWT.

### Endpoints:
- **POST /api/auth/register**
- **POST /api/auth/login**

### Input:
#### Registration:
```json
{
  "email": "user@example.com",
  "password": "securePass123",
  "role": "host" // or "guest"
}
