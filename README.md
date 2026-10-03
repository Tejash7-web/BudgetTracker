# Personal Budget Tracker

## Project Description

Personal Budget Tracker is a C# Windows Forms application that helps users manage their personal income and expenses. The application connects to a MySQL database to store and manage transaction information.

The application allows users to:

* Add income and expense transactions
* Select a transaction category and type
* Enter transaction date and description
* View transaction history
* Delete selected transactions
* View total income
* View total expenses
* View remaining balance

The application uses Object-Oriented Programming (OOP) concepts including classes and objects, encapsulation, inheritance, polymorphism and abstraction. Exception handling is also used to manage runtime and database errors.

## Software and Technologies Used

* C#
* .NET Windows Forms
* Visual Studio / Visual Studio Code
* MySQL Server
* MySQL Workbench
* MySQL Connector/NET

## How to Run the Application

### 1. Install the Required Software

Install the following software:

* Visual Studio with C# and Windows Forms support
* MySQL Server
* MySQL Workbench
* MySQL Connector/NET

### 2. Set Up the Database

Create a MySQL database named:

```text
PersonalBudgetDB
```

Create the required tables:

* `Category`
* `Type`
* `Transaction`

Add the required category and transaction type records.

### 3. Configure the Database Connection

The application uses the following connection string:

```csharp
string connStr = "Server=localhost;Database=PersonalBudgetDB;Uid=root;Pw=;";
```

Update the `Uid` and `Pw` values if your MySQL username or password is different.

### 4. Open the Project

Open the C# project in Visual Studio.

Make sure the MySQL Connector/NET package is installed and that the project can access:

```csharp
MySql.Data.MySqlClient
```

### 5. Build and Run

Build the project to check for errors.

Then run the application using the **Start** or **Run** button in Visual Studio.

The Personal Budget Tracker window should open.

### 6. Using the Application

1. Enter the transaction amount
2. Select a category
3. Select the transaction type
4. Select the date
5. Enter a description
6. Click **Add Transaction**
7. View the transaction in the transaction table
8. Select a transaction and click **Delete Selected** when required
9. The income, expenses and remaining balance are updated automatically

## References and Tools Used

### Development Tools

* Microsoft Visual Studio – used for C# application development and execution
* Visual Studio Code – used for code editing, where applicable
* MySQL Server – used for database storage
* MySQL Workbench – used for database creation and management
* MySQL Connector/NET – used to connect the C# application with MySQL

### GenAI Tools

* OpenAI (2026), *ChatGPT* – used for assistance with explaining OOP concepts, reviewing code structure and improving documentation.
* Microsoft (2026), *Microsoft Copilot* – used for coding assistance and explanations where applicable.

### Online References

* Microsoft (2026), *Visual Studio Code*, Microsoft, viewed 3 October 2026, https://code.visualstudio.com/
* Microsoft (2026), *C# documentation*, Microsoft, viewed 3 October 2026, https://learn.microsoft.com/en-us/dotnet/csharp/
* Oracle (2026), *MySQL documentation*, Oracle, viewed 3 October 2026, https://dev.mysql.com/doc/

## Author

Tejas Nepali

