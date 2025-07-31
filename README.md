# Nexus Hotel Docker Compose Demo

This project demonstrates a simple multi-service hotel application using Docker Compose.

## Services

1. **Frontend** - Main hotel website (port 80)
2. **Booking Service** - Room reservation system (port 8080)
3. **Admin Panel** - Hotel management dashboard (port 8081)

## Prerequisites

- Docker installed
- Docker Compose installed

## Setup Instructions

1. Clone this repository or create the files as shown in the structure
2. Place your images in the `images` directory (logo.png and hotel-exterior.jpg)
3. Run the application:

```bash
docker-compose up -d