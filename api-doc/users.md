# Users API (fitElle)

## Overview

This API allows managing users in the fitElle app.

---

## GET /users

Returns a list of users in the fitElle system.

### Request

GET /users

### Response

```json
[
  {
    "id": 1,
    "name": "Marina",
    "goal": "fitness"
  }
]
```
---

## POST /users

Creates a new user in the fitElle system.

### Request

```json
{
  "name": "Marina",
  "goal": "fitness"
}
```
### Response

```json
{
  "id": 2,
  "message": "User created successfully"
}
```
