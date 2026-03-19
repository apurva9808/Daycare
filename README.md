🏫 Daycare Management System

A Java-based Daycare Management System built using Java Swing, Spring, and H2 Database, designed to manage students, teachers, classrooms, and immunization records efficiently. The application follows a structured MVC architecture and incorporates key design patterns for scalability and maintainability.

🚀 Features

👶 Manage student records (add, update, view)

👩‍🏫 Manage teacher information and assignments

🏫 Classroom allocation and management

💉 Track immunization and vaccination records

📊 Interactive desktop UI using Java Swing

📁 Load initial data from CSV files

🔐 Structured application layers (Controller, Service, Repository)

🧠 Architecture

This project follows the MVC (Model-View-Controller) pattern:

Model → Core entities like Student, Teacher, Classroom, Immunization

View → Java Swing UI panels (forms, dashboards)

Controller → Handles user actions and connects UI with backend logic

🧩 Design Patterns Used

🏭 Factory Pattern → Object creation (Student, Teacher, Classroom)

📦 Repository Pattern → Data access and persistence

⚙️ Service Layer Pattern → Business logic separation

🧱 MVC Architecture → Clean separation of concerns

⚙️ Tech Stack

Language: Java

UI: Java Swing

Backend: Spring Framework

Database: H2 (Embedded Database)

Build Tool: Maven / Gradle (based on setup)

Data Source: CSV files

📂 Project Structure
src/
 ├── model/         # Entity classes (Student, Teacher, etc.)
 ├── view/          # Swing UI panels
 ├── controller/    # Handles user interactions
 ├── service/       # Business logic
 ├── repository/    # Database operations
 ├── factory/       # Factory pattern implementations
 └── data/          # CSV files and DB
🧑‍💻 Getting Started
Prerequisites

Java (JDK 8 or above)

IDE (IntelliJ / Eclipse recommended)

Maven or Gradle (if applicable)

Setup Instructions
# Clone the repository
git clone <your-repo-link>

# Navigate to project folder
cd Daycare-main

# Open in IDE and run MainFrame.java
Running the Application

Launch the project via MainFrame.java

The UI will open as a desktop application

Interact with modules (Students, Teachers, Classes, Immunization)

📊 Data Handling

Initial data is loaded from CSV files

Runtime data is stored in an H2 embedded database

🎯 Key Highlights

Modular and scalable architecture

Strong use of design patterns (important for interviews)

Clean separation of UI, logic, and data layers

Real-world use case for daycare management

📝 Future Improvements

Convert to web-based application (React + Spring Boot)

Add authentication and role-based access

Deploy on cloud (AWS / Docker)

Improve UI/UX design


