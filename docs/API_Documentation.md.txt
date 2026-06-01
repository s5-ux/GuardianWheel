# GuardianWheel API Documentation

## Authentication

### User Registration

POST /api/register

Request:
{
"name": "Sanjana",
"email": "[user@gmail.com](mailto:user@gmail.com)",
"password": "********"
}

Response:
{
"status": "success"
}

---

### User Login

POST /api/login

Request:
{
"email": "[user@gmail.com](mailto:user@gmail.com)",
"password": "********"
}

Response:
{
"token": "jwt_token"
}

---

## Fatigue Detection

GET /api/fatigue-status

Response:
{
"ear": 0.21,
"perclos": 0.42,
"status": "Drowsy"
}

---

## Driver Booking

POST /api/book-driver

Request:
{
"userId": "123",
"location": "Jamshedpur"
}

Response:
{
"driverAssigned": true
}

---

## SOS Alert

POST /api/sos

Request:
{
"userId": "123",
"latitude": 22.80,
"longitude": 86.20
}

Response:
{
"alertSent": true
}

---

## Nearby Drivers

GET /api/nearby-drivers

Response:
{
"drivers": [
{
"name": "Driver A",
"distance": "2 km"
}
]
}
