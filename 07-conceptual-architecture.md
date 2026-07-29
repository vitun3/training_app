# 7. Conceptual Architecture

## Overview
The system is organized around a core domain of training data and a social engagement layer. Users interact through a web application, while services manage plans, workouts, notifications, and social activity.

## Conceptual Components
- Client Applications: web frontend and mobile client.
- Core API: orchestrates business workflows.
- Domain Services: training management, social features, notification handling.
- Data Stores: relational database for core entities and object storage for media assets.
- Integration Services: email, push notification, and analytics providers.

## Architectural Style
The application follows a modular service-oriented design with clear separation of concerns to support evolution and independent scaling.
