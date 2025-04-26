# WebApiFormatter

An ASP.NET Core Web API that provides services for string and number formatting, along with validation utilities.

Covered with xUnit unit tests.

---

## Project Structure
```
WebApiFormatter/            # Main Web API project
Controllers/              # ReverseController (API endpoint)
Helpers/                  # Validation and formatting helpers
Models/                   # DTOs for requests and responses
Services/                 # Core formatting services
appsettings.json          # Application configuration
Program.cs                # Entry point
Startup.cs                # Application startup logic
WebApiUnitTests/            # Unit tests for API and services
```
---

## Features

- Format numbers and strings via a RESTful API.
- Validate input using helper utilities.
- Modular design with clear separation of concerns.
- Fully unit-tested with xUnit.

---

## Requirements

- .NET 6 SDK
- Visual Studio 2022 / Rider / VSCode

---

## Running the Project

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/WebApiFormatter.git
cd WebApiFormatter

2. Build and run the API

dotnet run --project WebApiFormatter

3. Access the API

http://localhost:5000/api/reverse



⸻

Running the Tests

To execute unit tests:

dotnet test WebApiUnitTests



⸻

API Overview

POST /api/reverse

Reverse the input string and format numbers.

Request:

{
  "text": "example123"
}

Response:

{
  "reversed": "321elpmaxe",
  "isValid": true
}



⸻

Best Practices Implemented
• Dependency Injection
• Separation of Concerns
• Interface-driven design
• xUnit unit testing
• Configurable environment settings

⸻



---

 Теперь весь текст читается чётко и красиво — без разъехавшихся блоков.  
 Все команды внутри кода или обёрнуты в `bash` или `json`, чтобы GitHub красиво подсветил.

---
