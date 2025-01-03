# Calendar Application for Communication Tracking

## Overview

This React-based Calendar Application is designed to efficiently track communications with companies, ensuring follow-ups are timely and consistent. It features an Admin Module for configuration, a User Module for interaction management, and an optional Reporting and Analytics Module for insights.

---

## Features

### Admin Module
- **Company Management**: Add, edit, and delete company details (e.g., name, location, LinkedIn profile, emails, phone numbers, comments, and communication periodicity).
- **Communication Method Management**: Configure communication methods with name, description, sequence, and mandatory status.

### User Module
- **Dashboard**: Grid view with company name, last five communications, and next scheduled communication.
  - **Color-coded Highlights**: Red (overdue) and Yellow (due today).
  - Hover tooltips for notes/comments.
- **Communication Action**: Log new communication, reset highlights.
- **Notifications**: Overdue and today’s communication grids.
- **Calendar View**: Interactive calendar to manage past and future communications.

### Reporting and Analytics Module (Optional)
- Communication frequency, engagement effectiveness, overdue communication trends, downloadable reports, and real-time activity logs.

---

## Getting Started

### Prerequisites
Ensure the following are installed on your system:
- [Node.js](https://nodejs.org/) (version 16 or above)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/invitha123/calender-application/edit/main/README.md
   cd calendar-application
