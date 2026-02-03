# Beauty Salon Management System

This project is a comprehensive **Beauty Salon Management System** built with **ASP.NET Core 9.0 MVC**. It allows users to book appointments, manages salon services and employees, and includes an admin panel for business operations.

## 🚀 Features

*   **User Authentication & Authorization**: Secure login and registration using ASP.NET Core Identity.
*   **Appointment Booking**: Users can browse services, select employees, and book appointments.
*   **Admin Dashboard**: Manage salons, employees, services (Islem), and view appointments.
*   **Employee Management**: Track employee details, working hours, and specialized services.
*   **AI Integration**: Includes an AI controller (`YapayZekaController`) for intelligent features (e.g., recommendations).
*   **API Support**: RESTful API endpoints for integration with other platforms.

## 🛠 Technology Stack

*   **Framework**: .NET 9.0 (ASP.NET Core MVC)
*   **Database**: PostgreSQL / SQL Server (Entity Framework Core)
*   **ORM**: Entity Framework Core
*   **Frontend**: Razor Views, HTML5, CSS3, JavaScript
*   **Tools**: Swagger (API Documentation)

## 📦 Getting Started

### Prerequisites

*   [.NET 9.0 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)
*   PostgreSQL or SQL Server (configured in `appsettings.json`)

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/web-programlama.git
    cd web-programlama
    ```

2.  Update the database connection string in `appsettings.json`.

3.  Apply database migrations:
    ```bash
    dotnet ef database update
    ```

4.  Run the application:
    ```bash
    dotnet run
    ```

5.  Open your browser and navigate to `https://localhost:7198` (or the port specified in the launch logs).

## 📂 Project Structure

*   **Controllers/**: Handles incoming requests and application logic (e.g., `RandevuController`, `AdminController`).
*   **Models/**: Database entities and ViewModels (e.g., `Randevu`, `Calisan`, `Salon`).
*   **Views/**: UI pages using Razor syntax.
*   **wwwroot/**: Static assets (CSS, JS, Images).

## 🤝 Contributing

1.  Fork the project
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request
