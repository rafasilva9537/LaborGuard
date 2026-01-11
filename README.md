# LaborFlow
ASP.NET 10 WebAPI using Clean Architecture, features employee resource management and a manual/auto-scheduler that strictly enforces labor compliance rules (11h rest periods, 40h weekly caps).

# Setup
## 1.Configure user secrets
```json
{
  "JwtConfig": {
    "Secret": "a-string-secret-at-least-256-bits-long",
    "Issuer": "http://localhost:7298/",
    "Audience": "http://localhost:7298/",
    "AccessTokenExpirationMinutes": "15",
    "RefreshTokenExpirationDays": "7"
  }
}
```
