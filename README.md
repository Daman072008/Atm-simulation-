# 🏧 ATM Simulation System (Python)

## 📌 Project Description

This project is a **simple ATM simulation system** developed using Python. It is a menu-driven program that allows users to perform basic banking operations such as checking balance, withdrawing money, depositing money, and viewing transaction history.

The system uses an infinite loop to continuously interact with the user until they choose to exit.

---

## 🚀 Features

* 💰 Display Account Balance
* 💸 Withdraw Money
* 💵 Deposit Money
* 📄 Transaction Statement (history of operations)
* 🔁 Menu-driven system using `while True` loop

---

## 🛠️ Technologies Used

* Python 3
* Basic concepts:

  * Functions
  * Loops (`while`)
  * Conditional statements (`if-else`)
  * Lists (for storing transactions)

---

## 📂 Project Structure

```
ATM-Simulation/
│── atm.py        # Main Python program
│── README.md     # Project documentation
```

---

## ▶️ How to Run the Project

1. Install Python (if not already installed)
2. Download or clone the repository:

   ```
   git clone https://github.com/your-username/ATM-Simulation.git
   ```
3. Navigate to the project folder:

   ```
   cd ATM-Simulation
   ```
4. Run the program:

   ```
   python atm.py
   ```

---

## 📋 Sample Menu

```
1. Display Balance
2. Deposit Money
3. Withdraw Money
4. View Statement
5. Exit
```

---

## 🧠 Working Logic

* The system starts with an initial balance.
* User selects options from the menu.
* Based on input:

  * Balance is displayed
  * Money is deposited or withdrawn
  * Transactions are stored in a list
* The loop continues until the user exits.

---

## 📊 Example Output

```
Enter your choice: 2
Enter amount to deposit: 500
Amount deposited successfully!

Enter your choice: 4
Transaction History:
Deposited: 500
```

---

## ⚠️ Limitations

* No real bank integration
* No user authentication (PIN system not included)
* Data is not stored permanently (resets after program ends)

---

## 🔮 Future Improvements

* Add PIN authentication 🔐
* Store data using files or database 💾
* GUI interface using Tkinter 🎨
* Multiple user accounts 👥

---

## 👨‍💻 Author

Daman Bassi
B.Tech CSE Student

---

## ⭐ Contribution

Feel free to fork this repository and improve the project!

---

## 📜 License

This project is open-source and free to use for learning purposes.
