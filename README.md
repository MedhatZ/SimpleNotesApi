# Simple Notes API

A simple REST API built with .NET 8 for managing notes.

## Features

- Create, Read, Update, Delete (CRUD) for notes
- SQLite database
- Swagger UI for testing

## Getting Started

### Requirements

- .NET 8 SDK

### Run the project

```bash
dotnet restore
dotnet ef database update
dotnet run
```

Then navigate to `https://localhost:5001/swagger` to use the API.

## License

MIT
