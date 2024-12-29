# SOAR Project ROOT

This repository contains a Docker Compose setup to run a the full SOAR app including frontend, backend, and database services.

## Prerequisites

Ensure you have the following installed:
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Getting Started

Follow these steps to set up and run the application:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/khedri-zineddine/SOAR
   cd SOAR
   git clone https://github.com/khedri-zineddine/soar-backend
   git clone https://github.com/khedri-zineddine/soar-frontend
   ```

2. **Start the application**:
   ```bash
   docker-compose up --build
   ```

3. **Access the services**:
   - **Frontend**: `http://localhost:8001`
   - **Backend**: `http://localhost:8002`
   - **Database**: Available at `localhost:6379`

## Services Overview

The Docker Compose setup includes:
- **Frontend**: Client-side application VueJS.
- **Backend**: Server-side API Flask.
- **Database**: Database MongoDB.

## Stopping the Application

To stop and remove the running containers, use:
```bash
docker-compose down
```
