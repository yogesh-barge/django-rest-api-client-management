# Django REST API for Client and Project Management

## Overview
This project provides a RESTful API built with Django to manage clients, users, and projects efficiently. It allows for the registration of clients, creation and management of projects, and retrieval of relevant information.

## Features
- **Client Management**: Register, update, and delete clients.
- **Project Management**: Create projects for clients and assign users.
- **User-Specific Projects**: Retrieve projects assigned to the logged-in user.

## Endpoints
- `GET /clients/`: List all clients.
- `POST /clients/`: Create a new client.
- `GET /clients/:id`: Retrieve client details with projects.
- `PUT /clients/:id`: Update client information.
- `DELETE /clients/:id`: Delete a client.
- `POST /clients/:id/projects/`: Create a new project for a client.
- `GET /projects/`: List projects assigned to the logged-in user.

## Installation
1. Clone the repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Run migrations: `python manage.py migrate`.
4. Start the server: `python manage.py runserver`.

## Usage
Access the API endpoints via your preferred API client or browser.

