
# Task Management API

## Project Description
A simple REST API for managing users and their tasks.

## Resources
- Users: Stores user information.
- Tasks: Stores tasks created by users.

## API Endpoints

### Users

| Method | Endpoint | Status Code |
|---|---|---|
| GET | /users | 200 OK |
| POST | /users | 201 Created |
| GET | /users/{id} | 200 OK |
| PUT | /users/{id} | 200 OK |
| DELETE | /users/{id} | 204 No Content |

### Tasks

| Method | Endpoint | Status Code |
|---|---|---|
| GET | /tasks | 200 OK |
| POST | /tasks | 201 Created |
| GET | /tasks/{id} | 200 OK |
| PUT | /tasks/{id} | 200 OK |
| DELETE | /tasks/{id} | 204 No Content |

## Architecture

Frontend → REST API → Backend → Database

## Important Feature
Users can create, update, view, and delete their tasks.
