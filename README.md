# PRT-System — Project Resource & Timesheet Management System

A full-stack web application for managing project budgets, resource allocation, and real-time timesheet tracking, with role-based dashboards for monitoring project health.


---

## Overview

PRT-System helps project teams track budgets, log resource hours, and monitor progress from a single dashboard. It enforces business rules such as preventing purchase order values from exceeding allocated project budgets, and gives managers role-based, real-time visibility into project health.

## Features

- **Home Dashboard** — at-a-glance overview of active projects and key metrics
- **Project Management** — create and manage projects, budgets, and purchase orders
- **Project Details** — drill into individual project data and resource allocation
- **Timesheet Tracking** — real-time logging and tracking of resource hours against projects
- **Reports** — generate reports for project health and resource utilization
- **Role-Based Access Control (RBAC)** — permission-scoped access across user roles
- **Business Rule Enforcement** — e.g., purchase order values are validated against project budgets
- **Normalized PostgreSQL Schema** — designed for data integrity and referential consistency

## Tech Stack

| Layer      | Technology                          |
|------------|--------------------------------------|
| Frontend   | Angular 15+, Tailwind CSS            |
| Backend    | Spring Boot 3.0, RESTful APIs        |
| Database   | PostgreSQL                           |
| Tooling    | Git, GitHub                          |

## Project Structure

```
PRT-System/
├── Backend/
│   └── src/          # Spring Boot application (APIs, business logic, DB layer)
├── Frontend/
│   └── src/           # Angular application (components, services, UI)
└── README.md
```

## Screenshots

#### Home Page
<img width="1918" height="966" alt="Home Page" src="https://github.com/user-attachments/assets/2e73f923-b2f4-46d0-9a8b-8b1e12bf7cef" />

#### Project
<img width="1913" height="956" alt="Project" src="https://github.com/user-attachments/assets/10336c51-8a6e-457d-8cd2-d0ac8cb5015b" />

#### Details
<img width="1892" height="960" alt="Details" src="https://github.com/user-attachments/assets/074b5a56-fda3-45ae-b1d9-8835c486dd30" />

#### Timesheet
<img width="1896" height="837" alt="Timesheet" src="https://github.com/user-attachments/assets/afa43766-b742-4375-a16b-30f6d27a5933" />

#### Reports
<img width="1896" height="962" alt="Reports" src="https://github.com/user-attachments/assets/f3f02163-dcb0-4109-afe7-57b76dca1a05" />

## Getting Started

### Prerequisites

- Node.js and npm
- Java 17+ and Maven
- PostgreSQL

### Backend Setup

```bash
cd Backend
# configure your PostgreSQL connection in src/main/resources/application.properties
mvn spring-boot:run
```

### Frontend Setup

```bash
cd Frontend
npm install
ng serve
```
