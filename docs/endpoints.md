# Endpoints

| Endpoint | Method | Auth | CRUD | Description |
| - | - | - | - | - |
| /visits | GET | nem | read | Reads visits |
| /visits/:id | GET | nem | read | Reads visit |
| /visits | POST | nem | create | Create a visit |
| /visits/:id | PUT | nem | update | Update a visit |
| /visits/:id | DELETE | nem | delete | Delete one visit |

## Create visit

* Method: POST
* Endpoint: /api/visits

```json
{
    "name": "Béla",
    "email": "bela@zold.lan",
    "eventId": 1
}
```
