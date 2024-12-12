# Employee Management System

Employee Management System is a Java-based application designed to efficiently manage employee records, providing functionalities such as adding, updating, viewing, and deleting employee details. This project utilizes **Java** for the backend, **SQL** for database management, and **Java Swing** and **AWT Toolkit** for the user interface.

---

## Features

- Add new employee records with details such as name, ID, department, and salary.
- Update existing employee information.
- Delete employee records securely.
- View a list of all employees in the database.
- Search employees by ID or name.
- Interactive and user-friendly GUI designed with Java Swing and AWT Toolkit.

---

## Technologies Used

- **Java**: Core programming language used for the application.
- **SQL**: To manage and store employee data in a database.
- **Java Swing**: For the graphical user interface.
- **AWT Toolkit**: Additional GUI components for enhanced functionality.

---

## Prerequisites

Ensure you have the following installed on your system:

1. **Java Development Kit (JDK)**
2. **MySQL Database**
3. An IDE like **Eclipse** or **IntelliJ IDEA** (optional but recommended)

---

## Setup Instructions

1. **Clone the Repository**
   ```
   git clone https://github.com/yourusername/employee-management-system.git
   ```

2. **Import the Project**
   - Open your preferred IDE.
   - Import the project as a Java project.

3. **Set Up the Database**
   - Create a database in MySQL.
   - Use the provided SQL file (`employee_management.sql`) to set up the required tables.

4. **Update Database Configuration**
   - Navigate to the database connection file in the project.
   - Update the database URL, username, and password.

5. **Run the Project**
   - Compile and run the application through your IDE.

---

## Usage

- Launch the application.
- Navigate through the GUI to manage employee records.
- Use the search functionality to locate specific employees quickly.

---

## Folder Structure

```
Employee Management System/
├── src/
│   ├── employee/management/system/
│   │   ├── AddEmployee.java
│   │   ├── conn.java
│   │   ├── login.java
│   │   ├── Main-Class.java
│   │   ├── RemoveEmployee.java
│   │   ├── Splash.java
│   │   ├── UpdateEmployee.java
│   │   ├── View_Employee.java
├── icons/
│   ├── images/
├── lib/
│   ├── jcalendar-tz-1.3.3-4.jar
│   ├── mysql-connector-java-8.0.28.jar
│   ├── ResultSet2xml.jar
├── employee_management.sql
├── README.md
```

---

## Contribution

Contributions are welcome! If you'd like to contribute to this project:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

---

## Author

Developed by **Deva Sainath**.

---

## Acknowledgments

- **OpenAI's ChatGPT** for guidance and suggestions.
- Java and MySQL documentation for resources and references.
