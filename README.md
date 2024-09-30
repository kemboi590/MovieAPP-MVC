# MovieApp

This is a simple BookStore API built with **ASP.NET Core** and **SQLite**. The API follows the **MVC** pattern and provides basic CRUD functionality for managing books in a MongoDB database.

## Features

- ASP.NET Core Web API using the MVC pattern and Razore pages
- SQLite for database storage.
- CRUD operations (Create, Read, Update, Delete) for managing books.
- Proper separation of concerns between Controllers, Models, and Views.

## Project Structure

## Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download) install it from the official website.
- SQLite
- Visual Studio or any preferred code editor.

## Setup and Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/kemboi590/MovieAPP-MVC.git
   cd BookStoreApi
   ```

2. **Install project dependencies**:

   ```bash
   dotnet restore
   ```

3. **appsettings.json file**:

- You will need to configure the MongoDB connection string and database settings in _appsettings.json_

```code
{
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning"
    }
  },
  "AllowedHosts": "*",
  "ConnectionStrings": {
    "MovieAppContext": "Data Source=MovieAppContext-toyourdb"
  }
}
```

4. **Run the Application**:

```code
dotnet run
```
