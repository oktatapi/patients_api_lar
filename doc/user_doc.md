# Endpoints

* /api/patients
* /api/visits

## Patinets endpoint

| Endpoint | Method | Auth | Description |
| - | - | - | - |
| /api/patients | GET | no | Get patients |
| /api/patients | POST | no | Create new patient |
| /api/patients/:id | GET | no | Get a patient |
| /api/patients/:id | PUT | no | Update a patient |
| /api/patients/:id | DELETE | no | Delete a patient |

### Get patients

* Method: GET
* /api/patients

### Create patient

* Method: POST
* /api/patients

Example JSON data to send:

```json
{
    "name": "John Doe",
    "birthDate": "1990-01-01",
    "socialNumber": "1234567890",
    "phone": "1234567890"
}
```

## Update patient

* Method: PUT
* Endpoint: /api/patinets/:id

Example:

* /api/patients/4

JSON data to send:

```json
{
    "name": "John Doe",
    "birthDate": "1990-01-01",
    "socialNumber": "1234567890",
    "phone": "1234567890"
}
```

## Delete patient

* Method: DELETE
* Endpoint: /api/patients/:id

Example:

* /api/patients/4
