# Coursera - Microsoft Full-Stack Developer

## Blazor for Front-End Development

### EventEase - Blazor Event Management App
EventEase is a modern web application built with Blazor (.NET 9) and Bootstrap. This project was developed as part of a technical assignment to demonstrate core Blazor capabilities, including component-based architecture, two-way data binding, form validation, and interactive state management.

### Features
Event Dashboard: Displays event details using a custom EventCard component.

Real-time Data Binding: Implements two-way data binding allowing instant updates of event information.

Registration System: A robust registration form with real-time field validation using DataAnnotations.

Attendance Tracker: An interactive management tool to track and update guest attendance status dynamically.

Responsive Design: Fully mobile-friendly UI built with Bootstrap.

### Copilot Assistance Summary
Microsoft Copilot served as an essential pair programmer throughout the development process:

Foundational Setup: It assisted in scaffolding the EventCard component and setting up the initial two-way data binding logic.

Routing & Navigation: Copilot helped resolve navigation lifecycle issues and ensured the NavMenu correctly mapped to the interactive pages.

Optimization: It provided the logic for the RegistrationModel validation and suggested the .NET 9 interactivity settings (InteractiveServer) required for real-time UI updates.

State Management: Copilot helped design the logic for the Attendance Tracker to ensure the UI reflects data changes immediately.

###  Technical Stack
Framework: .NET 9 (Blazor Web App)

Interactivity Mode: Interactive Server

Styling: Bootstrap 5

Language: C# / Razor

###  How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/AdemOzcelik/EventEase-Blazor-App.git
```
2. Navigate to the project folder:
```bash
cd EventEaseApp
```
3. Run the application:
```bash
dotnet watch
```
