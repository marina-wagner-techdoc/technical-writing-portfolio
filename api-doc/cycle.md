# Cycle API (fitElle)

## Overview

This API allows tracking and managing menstrual cycle data in the fitElle app.

---

## GET /cycle

Returns cycle entries for a user.

### Request

GET /cycle

### Response

```json
[
  {
    "date": "2026-06-01",
    "phase": "follicular",
    "symptoms": ["low energy"]
  },
  {
    "date": "2026-06-02",
    "phase": "ovulation",
    "symptoms": ["high energy"]
  }
]
```
---

## POST /cycle

Creates a new cycle entry.

### Request

```json
{
  "date": "2026-06-03",
  "phase": "luteal",
  "symptoms": ["fatigue"]
}
```
### Response

```json
{
  "message": "Cycle entry created successfully"
}
```
