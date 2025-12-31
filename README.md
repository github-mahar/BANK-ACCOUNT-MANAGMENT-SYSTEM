# 🏦 Bank Account Management System


[![Java](https://img.shields.io/badge/Java-25-orange?logo=java&logoColor=white)](https://www.oracle.com/java/) 
[![License](https://img.shields.io/badge/License-MIT-green)](#license)

---

## 📌 Overview
**Bank Account Management System** is a Java-based project demonstrating **Object-Oriented Programming (OOP)** concepts.  

It allows users to:

- Create and manage bank accounts  
- Check balances  
- Deposit and withdraw money  
- Perform basic banking operations  

This project is ideal for learning **inheritance, encapsulation, and polymorphism** in Java.

---

## 🗂️ Project Structure

```
BANK-ACCOUNT-MANAGMENT-SYSTEM-/
│
├── Account.java              # Base class for bank accounts
├── Accountdriver.java        # Main driver class to run the application
├── Checkingaccount.java      # Subclass for checking accounts
├── Savingaccount.java        # Subclass for savings accounts
├── Account.class             # Compiled class for Account
├── Accountdriver.class       # Compiled class for Accountdriver
├── Checkingaccount.class     # Compiled class for Checkingaccount
├── Savingaccount.class       # Compiled class for Savingaccount
└── README.md                 # Project documentation
```

---

## 📑 Table of Contents
- [Prerequisites](#️-prerequisites)  
- [Setup & Run](#-setup--run)  
- [Notes](#-notes)  
- [Best Practices](#-best-practices)  
- [Author](#-author)  
- [License](#-license)  

---

## ⚙️ Prerequisites
- **Java JDK 8 or above** installed  
- Verify installation:
```bash
java -version
javac -version

    If not installed, download OpenJDK

    Ensure %JAVA_HOME%\bin is added to your system PATH
```

## 🚀 Setup & Run
<details> <summary>1️⃣ Clone the Repository</summary>

```bash
git clone https://github.com/DevaGhawat/BANK-ACCOUNT-MANAGMENT-SYSTEM-.git
cd BANK-ACCOUNT-MANAGMENT-SYSTEM-
```

</details> <details> <summary>2️⃣ Compile Java Files (if needed)</summary>

If .class files are missing:

```bash
javac *.java
```

For subfolders:

```bash
Get-ChildItem -Recurse -Filter *.java | ForEach-Object {$_.FullName} > sources.txt
javac @sources.txt
```

</details> <details> <summary>3️⃣ Run the Application</summary>

```bash
java Accountdriver
```

If classes are inside a package:

```bash
java packageName.Accountdriver
```

</details>

## 💡 Notes

- .class files are included to allow running without compiling.
- Best practice: Track only .java files in Git and ignore .class files using .gitignore.

## ✅ Best Practices

- Keep .java files versioned in Git
- Use .gitignore to exclude .class files
- Use an IDE (IntelliJ, Eclipse, VS Code) for easier compilation and running

## 👤 Author

Mahar Ghulam Muhammad  
SAP ID: 70167841

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

