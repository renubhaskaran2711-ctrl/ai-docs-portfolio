## Endpoint Title 

```
PUT /users/{id}
```

## Description

Updates the details of a specific user by ID

## Authentication

Requires bearer token authentication

## Path Parameters

| Parameter | Type | Parameter |
|--------|----------|
| GET    | Retrieve data |
| POST   | Create data |
| PUT    | Update data |
| DELETE | Remove data |

|Parameter| Type | Required | Description| 
------------------------------------------
|name|string| Yes| Name of the user|
-------------------------------------------------------
|email|string | Yes| email ID of the user|

Response returns updated user object.
