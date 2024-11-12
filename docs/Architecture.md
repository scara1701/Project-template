# Project Architecture

## Overview
Provide a brief overview of the project architecture. Describe the main components and their interactions.

## Components

### Client
- **Technology**: .NET MAUI
- **Description**: The client application for user interaction.
- **Responsibilities**: User interface, data binding, interaction with the server.

### Server
- **Technology**: ASP.NET Core
- **Description**: The backend service handling API requests.
- **Responsibilities**: Business logic, data processing, file storage.

### Core
- **Description**: Contains shared services and business logic.
- **Responsibilities**: Core functionality used by both client and server.

### Shared
- **Description**: Shared models and libraries.
- **Responsibilities**: Data models and utilities shared between the client and server.

### Repositories
- **Description**: Data access layer.
- **Responsibilities**: Interacting with the database or other data storage mechanisms.

### Utils
- **Description**: Utility functions and services.
- **Responsibilities**: Common helper functions, hash computation, file operations.

## Data Flow
Describe how data flows between different components. Include diagrams if necessary.

## Database Schema
Provide details about the database schema, including tables and their relationships.

## Security
Outline the security measures in place, such as authentication, authorization, and encryption.

## Deployment
Explain how to deploy the application, including any dependencies and configurations.
