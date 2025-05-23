# ATM Simulation System in Java

This project simulates an ATM (Automated Teller Machine) system using Java. It allows users to log in with a valid ATM number and PIN, then perform banking operations like checking balance, depositing, withdrawing, and viewing a mini-statement.

## 📁 Project Structure

atm/
├── AtmMain.java # Main class to drive the program
├── AtmOperationInterf.java # Interface defining ATM operations
├── AtmOperationImpl.java # Implementation of ATM operations

markdown
Copy
Edit

## 🚀 Features

- ATM Login (with ATM number and PIN)
- View Available Balance
- Withdraw Money
- Deposit Money
- View Mini Statement
- Exit System

## 🛠️ Technologies Used

- Java (JDK 8+)
- Scanner for input handling
- Object-Oriented Programming (OOP) principles

## 🧑‍💻 How to Run

1. **Clone the repository** (if hosted online) or download the project files.
2. Compile the Java files:
   ```bash
   javac atm/*.java
Run the main class:

bash
Copy
Edit
java atm.AtmMain
Use the following credentials when prompted:

ATM Number: 12345

ATM PIN: 123

💡 Sample Interaction
text
Copy
Edit
Welcome to ATM Machine!
Enter ATM number: 12345
Enter PIN: 123

1. View Available Balance
2. Withdraw Amount
3. Deposit Amount
4. View Mini Statement
5. Exit
Enter choice:
🔒 Security Note
This is a basic simulation project. Real-world ATM systems require robust security, encryption, transaction management, and database integration.

📌 Future Improvements
Add support for multiple users

Integrate with a database

Implement password masking

Use GUI (Swing/JavaFX) for better interaction
