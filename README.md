## 🔐 Users Endpoints [authentication]

| Action      | Endpoint                   | Method | Required Fields                                      |
|-------------|----------------------------|--------|------------------------------------------------------|
| Register    | `/api/users/register/`     | POST   | `username`, `email`, `password1`, `password2`        |
| Login       | `/api/users/token/`        | POST   | `username`, `password`                               |
| Refresh     | `/api/users/token/refresh/`| POST   | `refresh`                                            |
| Logout      | `/api/users/logout/`       | POST   | `Authorization: Bearer <access_token>`, `refresh`    |
| Get Profile | `/api/users/profile/`      | GET    | `Authorization: Bearer <access_token>`               |

---
