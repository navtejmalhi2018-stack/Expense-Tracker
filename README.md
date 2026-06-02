# Expense Tracker

A web application built with ASP.NET Core for tracking personal expenses and managing budgets.

## Features
- Add, edit, and delete expense entries
- Categorise expenses (e.g. Food, Transport, Entertainment)
- View expense history and summaries
- RESTful API architecture

## Technologies
- ASP.NET Core Web API
- C# / .NET
- Entity Framework Core
- SQL Server

## Endpoints

### Expenses
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/expenses` | Get all expenses |
| GET | `/expenses/{id}` | Get a specific expense |
| POST | `/expenses` | Add a new expense |
| PUT | `/expenses/{id}` | Update an expense |
| DELETE | `/expenses/{id}` | Delete an expense |

### Example — Add an Expense (POST /expenses)
\```json
{
  "title": "Groceries",
  "amount": 85.50,
  "category": "Food",
  "date": "2026-06-02"
}
\```

## Getting Started
1. Clone the repository
2. Open in Visual Studio or VS Code
3. Run the project
