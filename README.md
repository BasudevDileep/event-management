# Event Management and Booking System

A modern single-page application (SPA) built with Angular 17+ and TypeScript.

## Features
- **Browse Events:** View all upcoming events in a card-based layout.
- **Filtering & Search:** Search events by keyword and filter by category.
- **Event Details:** View detailed information, schedule, and speakers for each event.
- **Booking System:** Reactive form-based ticket booking with validation.
- **Manage Bookings:** View and cancel your bookings in the "My Bookings" section.
- **Authentication:** Mock login system to protect the bookings area.
- **Contact Us:** Template-driven form for inquiries.
- **Custom Highlights:** Custom directive to highlight featured or sold-out events.

## Tech Stack
- **Framework:** Angular 17 (Standalone Components)
- **UI Library:** Angular Material
- **Data:** Mock JSON and LocalStorage for persistence
- **Validation:** Both Reactive and Template-driven forms

## Setup Instructions
1. Navigate to the project directory:
   ```bash
   cd event-management-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   ng serve
   ```
4. Open your browser and navigate to `http://localhost:4200`

## Implementation Details
- **Routing:** Nested routes for event schedules and speakers, route guards for booking access.
- **Services:** Centralized services for event and booking data management.
- **Directives & Pipes:** Custom `appHighlightEvent` directive and `eventFilter` pipe for enhanced UI/UX.
- **Material UI:** Extensive use of MatCard, MatTable, MatDialog, MatToolbar, etc.
