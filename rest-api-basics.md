Scenario: User Resource Endpoints
Base URL: https://www.api.com/users
Resource: Users
Authentication: Required for all except GET /users
Body: JSON where applicable
We’ll document:
GET /users/{id} – retrieve a user
POST /users – create a user
PUT /users/{id} – update a user
DELETE /users/{id} – delete a user

## GET /users/{id}

## Description

Retrieves the details specific to the user ID.

## Authentication

Authentication is not required.

## Path Parameters

| Parameter | Type | Required | Description |
|-----------|------|----------|-------------|
| id | string | Yes | Unique identifier of the user |

## Example Request

```bash

curl -X GET https://https://www.api.com/user/{id}
  -d '{id: 123}'
