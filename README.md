 # BooksCrudOps-RazorPages

## Overview
BooksCrudOps-RazorPages is a simple **CRUD (Create, Read, Update, Delete)** application built with **ASP.NET Core Razor Pages**. It allows users to manage a collection of books, performing basic operations such as adding, editing, deleting, and viewing books.

## Features
- 📖 List all books
- ➕ Add new books
- ✏️ Edit book details
- 🗑️ Delete books


## Technologies Used
- **.NET 8**
- **ASP.NET Core Razor Pages**
- **Entity Framework Core**
- **SQL Server**
- **Bootstrap (for UI styling)**

## Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/devprince116/BooksCrudOps-RazorPages.git
cd BooksCrudOps-RazorPages
```

### 2️⃣ Configure Database
- Update the `appsettings.json` file with your **SQL Server connection string**.
- Run the following command to apply migrations:
```sh
dotnet ef database update
```

### 3️⃣ Run the Application
```sh
dotnet run
```
The application should now be running on **http://localhost:5000** (or the port specified in `launchSettings.json`).

## Usage
- Open your browser and navigate to `http://localhost:7169`
- Click on **Books** in the navigation menu
- Add, edit, delete, and view books seamlessly
