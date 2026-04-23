# Personal Finance Management System

A streamlined and efficient application designed to help users track their personal finances, manage daily expenses, and maintain a balanced monthly budget. 

This project focuses on structured data manipulation, efficient categorization of transactions, and robust data persistence.

## 🛠 Project Structure

* **/src**: Source code containing the core logic, categorized by modules (e.g., transactions, users, reports).
* **/data**: Persistence files (e.g., CSVs or databases) used to store the transaction history and user records.
* **/tests**: Automated test cases and mock data for system validation.

## 🚀 Key Features

* **Expense & Income Tracking**: Log daily transactions with dynamic categories.
* **Budget Management**: Monitor monthly spending limits against actual expenses.
* **Data Persistence**: Securely store and retrieve financial history without data loss between sessions.
* **Financial Summaries**: Generate quick reports on financial health over custom periods.

## 💻 Tech Stack

* **Language**: [Insert Language, e.g., C / C++ / Python / Dart]
* **Framework/Tools**: [Insert Tools, e.g., Flutter / GCC compiler]
* **Data Storage**: [Insert Storage Method, e.g., Local File System (CSV) / SQLite]

## ⚙️ Compilation and Execution

[Adjust the instructions below based on your specific language. The example below is for a C/C++ environment:]

To compile and run the project on a Linux environment using `gcc`:

```bash
# Clone the repository
git clone [https://github.com/Luciano-Tadeu/Sistema-Financas-Pessoais.git](https://github.com/Luciano-Tadeu/Sistema-Financas-Pessoais.git)

# Navigate to the source directory
cd Sistema-Financas-Pessoais/src

# Compile the application
gcc -o finance_manager main.c transactions.c data_handler.c -Wall

# Run the system
./finance_manager
