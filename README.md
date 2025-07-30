# 💰 Budget Buddy – Python Expense Tracker (SQLite)

## 📷 Demo Screenshot
<img src="https://github.com/user-attachments/assets/abec74ea-1d1f-4695-b430-85d8ae5c79ad" alt="Expense Tracker Demo" width="500" height="600">





**Budget Buddy** is a simple **command-line Expense Tracker** built in Python using an SQLite database.  
It allows you to **add, view, and analyze** your expenses easily with local database storage.

---

## 📜 Description
Budget Buddy is a **console-based application** that stores expenses in a local SQLite database (`expenses.db`).  
You can:
- Add daily expenses
- View all expenses
- Generate monthly expense reports

---

## ⚡ Features
✅ Add expense with **amount, category, description**  
✅ View all expenses in a clean format  
✅ Generate **monthly total expenses**  
✅ Data is stored permanently using **SQLite**  
✅ Simple and easy-to-use menu  

---

## 🛠️ Technologies Used
- **Python 3.x**
- **SQLite3** (built-in Python library)
- **time** module (for date formatting)

---

## 📂 Database Structure
**Table:** `expenses`

| Column Name | Type    | Description |
|-------------|---------|-------------|
| id          | INTEGER | Auto Increment Primary Key |
| amount      | REAL    | Expense amount (₹) |
| category    | TEXT    | Expense category (e.g., Food, Travel) |
| description | TEXT    | Notes for the expense |
| date        | TEXT    | Date of expense (YYYY-MM-DD) |

---

## 🚀 How to Run
1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/Budget-Buddy-Python-Expense-Tracker.git
cd Budget-Buddy-Python-Expense-Tracker
```

2. **Run the Python Script**
```bash
python expense_tracker.py
```

---

## 📜 Usage
When you run the program, you will see:

```
📌 Expense Tracker Menu
1. Add Expense
2. View Expenses
3. Monthly Report
4. Exit
```

**Example:**

- **Option 1** → Enter amount, category, and description to add an expense  
- **Option 2** → View all expenses stored in the database  
- **Option 3** → Enter month/year to get total monthly expenses  
- **Option 4** → Exit the program  

---

## 🖥 Example Output
```
📌 Expense Tracker Menu
1. Add Expense
2. View Expenses
3. Monthly Report
4. Exit
Enter Choice: 1
Enter amount: ₹250
Enter category: Food
Enter description: Lunch at cafe
✅ Expense added successfully!

📌 Expense Tracker Menu
Enter Choice: 2
📜 Expense List:
ID: 1, Amount: ₹250.0, Category: Food, Desc: Lunch at cafe, Date: 2025-07-29
```

---

## 📌 Future Improvements
- Category-wise monthly report  
- Export to CSV/Excel  
- Graphs & charts using **Matplotlib**  
- GUI version with **Tkinter/PyQt**
