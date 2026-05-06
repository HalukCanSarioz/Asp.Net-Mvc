
# 🖥️ ASP.NET MVC Samples
### (A Collection of ASP.NET MVC Learning Examples & Mini Projects)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![ASP.NET MVC](https://img.shields.io/badge/ASP.NET%20MVC-512BD4?style=flat&logo=.net&logoColor=white)](#)
[![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)](#)
[![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoft-sql-server&logoColor=white)](#)

This repository contains step‑by‑step **ASP.NET MVC** projects and code samples that teach the fundamentals of the Model‑View‑Controller architecture, Entity Framework integration, and building dynamic web applications with C#.

## 📚 Table of Contents
- [About the Project](#about-the-project)
- [What You’ll Learn](#what-youll-learn)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## About the Project
This project was created to master the core concepts of **ASP.NET MVC** – from routing and controllers to Razor views and data access with Entity Framework. Each example is a small, self‑contained demo that focuses on one or two key topics, making it easy to follow and reuse.

- **Developer:** Haluk Can SARIÖZ
- **Framework:** ASP.NET MVC (C#)
- **Purpose:** Learn and practice the Model‑View‑Controller pattern
- **Database:** SQL Server (LocalDB or Express) via Entity Framework

---

## What You’ll Learn
The examples in this repository cover:

- **MVC Fundamentals:** Controllers, Actions, and Action Results
- **Routing:** Convention‑based routing, attribute routing, and route constraints
- **Views & Razor Syntax:** Layout pages, partial views, and view data passing
- **Models & Data Annotations:** Validation, display attributes, and model binding
- **Entity Framework:** Code‑First migrations, LINQ queries, and CRUD operations
- **Forms & User Input:** Form submissions, model binding, and anti‑forgery tokens
- **State Management:** Session, TempData, and ViewData/ViewBag
- **Authentication & Authorization:** Basic identity examples (if present)

All projects are broken into small, focused folders so you can study one concept at a time.

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| **Backend** | C# / ASP.NET MVC |
| **ORM** | Entity Framework 6 / Core |
| **Database** | SQL Server (LocalDB) |
| **Frontend** | Razor views, Bootstrap, jQuery |
| **IDE** | Visual Studio / Visual Studio Code |
| **Version Control** | Git & GitHub |

---

## Getting Started

### Prerequisites
- [Visual Studio](https://visualstudio.microsoft.com/) (with the “ASP.NET and web development” workload) **OR** [Visual Studio Code](https://code.visualstudio.com/) with the C# extension
- [SQL Server LocalDB](https://docs.microsoft.com/en-us/sql/database-engine/configure-windows/sql-server-express-localdb) (included with Visual Studio) or SQL Server Express
- Git

### Steps

**1. Clone the repository:**
```bash
git clone https://github.com/halukcansarioz/Asp.Net-Mvc.git
cd Asp.Net-Mvc
```

**2. Open the project:**
Open the `.sln` file with Visual Studio, or open the root folder with VS Code.

**3. Restore NuGet packages:**
In Visual Studio, right‑click the solution and select “Restore NuGet Packages”. In VS Code, run:
```bash
dotnet restore
```

**4. Update the database (if using Entity Framework):**
```bash
Update-Database   # in Package Manager Console (Visual Studio)
```
or
```bash
dotnet ef database update
```

**5. Run the application:**
Press `F5` (Visual Studio) or execute:
```bash
dotnet run
```
The app will open at `https://localhost:5001` (or `http://localhost:5000`).

---

## Project Structure
```text
Asp.Net-Mvc/
├── MvcIntro/                  # Basic MVC project – controllers, views, routing
├── EntityFrameworkDemo/       # CRUD with Entity Framework
├── FormValidation/            # Models, data annotations, validation
├── PartialViewExample/        # Reusing views with partials
├── AuthenticationExample/     # Simple login/logout (if applicable)
├── .gitattributes
├── README.md
└── LICENSE
```
*(Folder names may differ; the structure above reflects typical topics.)*

---

## Contributing
Additional examples, bug fixes, or improvements are always welcome!

1. **Fork** this repository.
2. **Create a branch** (`git checkout -b feature/new-mvc-example`).
3. Make your changes and **commit** (`git commit -m 'Add: Example for TempData'`).
4. **Push** your branch (`git push origin feature/new-mvc-example`).
5. Open a **Pull Request**.

---

<a name="contact"></a>
## Contact
**Haluk Can Sarıöz**
- GitHub: [@halukcansarioz](https://github.com/halukcansarioz)
- Email: [halukcansarioz19@gmail.com](mailto:halukcansarioz19@gmail.com)
- LinkedIn: [Haluk Can Sarıöz](https://www.linkedin.com/in/halukcansarioz)

---

*If this collection helps you learn ASP.NET MVC, please ⭐ the repository!*

---

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and share.
