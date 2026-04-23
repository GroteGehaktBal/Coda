# Coda

Coda is web application where users can track the drinks they have tried.
The goal is to help users remember which drinks they liked and discover new ones.

## Tech stack

- Backend : Django REST API
- Frontend : React + Vite
- Database : PostgreSQL
- Containerization: Docker

## Architecture

- **Backend** - Django API responsible for data storage and business logic.
- **Frontend** - React application that communicates with the backend API.

The frontend communicates with the backend via HTTP API requests.

## Project structure
Coda <br>
|__ backend/ # Django backend <br>
|__ frontend/ # React frontend <br>
|__ docs/ # Project documentation

## Running the project
Backend and frontend are started separately. <br>
See the setup instructions in the individual folders:
- [backend setup](backend/READM.md)
- [frontend setup](frontend/READM.md)