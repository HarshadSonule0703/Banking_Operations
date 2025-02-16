# Secure Bank (Banking Operation)

A **Banking Management System** built using **JDBC, Java, Servlets, and MySQL**. This project provides basic **CRUD (Create, Read, Update, Delete)** operations for managing customer accounts.

## Features
- Customer Registration
- Account Balance Check
- Deposit & Withdrawal Transactions
- Updating Customer Details
- Deleting Customer Records

## Technologies Used
- **Java (JDBC, Servlets)**
- **Oracle** (Database)
- **HTML, CSS, JavaScript** (Frontend UI)
- **Tomcat** (Server)

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- Java Development Kit (JDK)
- Apache Tomcat Server
- Oracle Database
- Any IDE (Eclipse, IntelliJ, NetBeans)

### Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/HarshadSonule0703/Banking_Operations.git
   ```
2. Import the project into your IDE.
3. Configure Oracle Database:
   - Create a database and import the provided file.
   - Update database connection details in `DBConnection.java`.
4. Deploy the project on **Tomcat Server**.
5. Access the application via `http://localhost:8080/BankingSystem`.

## Database Schema
- **Customers Table**:
  - `id` (Primary Key)
  - `name`
  - `email`
  - `account_number`
  - `balance`

- **Transactions Table**:
  - `transaction_id` (Primary Key)
  - `account_number`
  - `type` (Deposit/Withdraw)
  - `amount`
  - `timestamp`

## Folder Structure
```
BankingSystem/
│── src/
│   ├── dao/  # Data Access Layer (JDBC)
│   ├── model/  # Java Beans
│   ├── servlet/  # Business Logic
│── webapp/
│   ├── index.html
│   ├── dashboard.html
│── WEB-INF/
│   ├── web.xml
```

## Contributing
Feel free to fork this repository and contribute with new features or improvements.



## Author
- **Harshad**
- GitHub: [Harshad](https://github.com/HarshadSonule0703)
