
# RoadGuard - System Architecture

## Overview
RoadGuard follows a modular architecture consisting of a frontend, backend, database and AI detection service.

## Main Components

### 1. Frontend
- HTML
- CSS
- JavaScript
- User interface and interaction

### 2. Backend
- Node.js
- Express.js
- REST API endpoints
- Request handling

### 3. Database
- MongoDB
- Stores pothole reports and related information

### 4. AI Service
- Python
- YOLO object detection model
- Analyses images for possible potholes

### 5. Location and Maps
- GPS / Geolocation API
- Leaflet maps
- Displays pothole locations

## Application Workflow

1. User opens RoadGuard.
2. User captures an image or submits a report.
3. The backend processes the request.
4. The AI service analyses the image when available.
5. GPS coordinates are associated with the report.
6. Report information is stored in MongoDB.
7. Available reports are displayed on the map and dashboard.

## Project Status
Architecture is proposed and subject to updates during implementation.
