# SimpleBlog

SimpleBlog is a lightweight blogging platform built using ASP.NET Core MVC. It features CRUD operations for blog posts and includes user authentication, allowing for an admin role that manages blog content.

## Features

- View, create, edit, and delete blog posts.
- Rich text support for blog post content.
- Responsive design that looks good on desktop and mobile devices.
- User authentication system with an admin role for blog management.

## Technology Stack

- **ASP.NET Core MVC**: For building the server-side application
- **Entity Framework Core**: For data access and ORM
- **SQL Server**: As the backend database

## Getting Started

### Prerequisites

- .NET Core SDK 2.1 
- Visual Studio 2022 or later (or compatible IDE with C# support)
- SQL Server (LocalDB or SQL Express)

### Setup and Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Vivek9602/Blog_Assessment.git
   cd Blog_Assessment/Blog
2. **Setup Database**
    Powershell: sqllocaldb create "localDB1"
    Change Connection String
4. **Run the program**
     dotnet restore
     dotnet build
     dotnet run

### Credentials
Admin: 
User: admin
Password: password

Test User:
User: testuser
Password: testpass
