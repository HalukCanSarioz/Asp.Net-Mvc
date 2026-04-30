# 🌐 TimeZona - ASP.NET MVC Demo Project

Welcome to the **TimeZona** repository! This is a DEMO project in ASP.NET MVC specifically designed for beginners to demonstrate core backend concepts, routing, and database management using Microsoft's ASP.NET MVC framework and C#.

## 👨🏼‍💻 About the Developer & Motivation

I have been trying to improve myself since I graduated from Ankara University Computer Engineering. For this, I attend courses from online platforms. I have about 6 months of experience on Ruby on Rails as a Full Stack Developer. I am currently trying to improve myself in Front-end and Back-end. The courses I take are on these topics and I develop projects on my own. This repository is a practical project I developed to expand my backend skills into the .NET ecosystem!

## ✨ Features

*   **MVC Architecture:** Clean separation of application logic (Controllers), data (Models), and user interface (Views).
*   **CRUD Operations:** Full Create, Read, Update, and Delete functionality for application entities.
*   **Database Integration:** Utilizes MS SQL Server with a pre-configured `.bacpac` data tier application.
*   **Admin Panel:** Built-in dashboard for administrative management.
*   **Routing:** Standardized and clean URL routing configurations.

## 🛠️ Tech Stack

*   **Language:** C#
*   **Framework:** ASP.NET MVC
*   **Database:** MS SQL Server
*   **Frontend:** Razor Views (.cshtml), HTML5, CSS3
*   **IDE:** Visual Studio
*   **Version Control:** Git & GitHub

## 🚀 Getting Started

Follow these instructions to set up the database and run the TimeZona project on your local machine.

### Prerequisites

Ensure you have the following installed on your system:
*   [Visual Studio](https://visualstudio.microsoft.com/)
*   MS SQL Server (SQL Server Management Studio - SSMS)
*   Git

### Installation & Database Setup

1.  **Clone the repository:**
    
    ```bash
    git clone https://github.com/halukcansarioz/Asp.Net-Mvc.git
    cd Asp.Net-Mvc
    ```

2.  **Database Part (TimeZona):**
    *   First, open MS SQL Server and create a new database named: `TimeZona`
    *   In order to use the pre-filled database, you need to import/run the `TimeZona.bacpac` file included in this project repository.
    *   *Need help importing a .bacpac file?* You can get help from this tutorial video: **[Watch how to import .bacpac in MSSQL](https://www.youtube.com/watch?v=4aTq2ayHEJ0&t=1s&ab_channel=Rumeysa)**

3.  **Configure Connection Strings:**
    *   Open the project solution in Visual Studio.
    *   Navigate to the `Web.Config` file.
    *   Make changes to the `ConnectionStrings` section to match your local MS SQL Server credentials and instance name.

4.  **Run the Application:**
    After making changes in the connection strings, press `F5` or click the **Start** button in Visual Studio to run this project.

### 🔐 Admin Panel Access

To access the administrative features of the application, use the following default credentials:

*   **UserID:** `Admin`
*   **Password:** `12345`

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
Feel free to check the [issues page](https://github.com/halukcansarioz/Asp.Net-Mvc/issues) if you want to contribute.

## 📜 License

This project is open-source and available under the MIT License - see the LICENSE file for details.

## 📫 Contact

**Haluk Can Sarıöz**
*   **GitHub:** [@HalukCanSarioz](https://github.com/HalukCanSarioz)
*   **Email:** halukcansarioz19@gmail.com
*   **LinkedIn:** [Haluk Can Sarıöz](https://www.linkedin.com/in/halukcansarioz)

---
*If this ASP.NET MVC beginner demo helped you, please consider giving the repository a ⭐!*
