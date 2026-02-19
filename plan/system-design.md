# System Design — Student Management System

## 1. Architecture Overview
The system follows a simple 3-layer architecture:

Presentation Layer → Application Logic → Database Layer

---

## 2. Components

### 2.1 User Interface
Handles interaction with the user.
Examples:
- Add student
- View records
- Enter grades

### 2.2 Application Layer
Contains business logic:
- Validation of inputs
- Managing relationships between students and courses
- Processing database queries

### 2.3 Database Layer
Responsible for:
- Storing student, course, and grade data
- Ensuring referential integrity
- Executing SQL queries

---

## 3. Data Flow

1. User enters request
2. Application validates input
3. SQL query is executed
4. Database returns result
5. Output displayed to user

---

## 4. Design Principles Used
- Separation of Concerns
- Modular Development
- Data Integrity via Constraints
- Scalability for future web integration

---

## 5. Planned Technologies
- Language: Python / Java (implementation phase)
- Database: MySQL / PostgreSQL / SQLite
- Version Control: Git + GitHub
