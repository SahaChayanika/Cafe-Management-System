# ☕ Cafe Management System (Python)

Welcome to the **Cafe Management System** project! This is a beginner-friendly Python program that simulates a simple ordering experience at a cafe. It allows customers to view a menu, place orders, and receive a bill total based on selected items.

## 📋 Features

- 🍽️ Menu display with item names and prices
- 🛒 Single or dual item order capability
- ❌ Validates if the ordered item exists in the menu
- 💵 Calculates total cost of ordered items
- 🖥️ Command-line interaction

## 💡 Technologies Used

- Language: **Python 3**
- Platform: **Command Line / Terminal**

## 🧾 Menu Items and Prices

| Item     | Price (INR) |
|----------|-------------|
| Pizza    | ₹140        |
| Biriyani | ₹180        |
| Pasta    | ₹50         |
| Burger   | ₹60         |
| Samosa   | ₹25         |
| Salad    | ₹70         |
| Coffee   | ₹80         |

## ▶️ How to Run

1. **Clone or download** the repository.
2. Make sure Python 3 is installed on your machine.
3. Run the script using:
   ```bash
   python cafe_management.py
Welcome to THE DELICIOUS Resturant
Pizza: Rs140
Biriyani: Rs180
Pasta: Rs50
Burger: Rs60
Samosa: Rs25
Salad: Rs70
Coffee: Rs80

Enter the name of item you want to order = Pizza
Your item Pizza has been added to your order
Do you want to add another item? (Yes/No) Yes
Enter the name of the second item you want to order = Coffee
Item Coffee has been added to order
The total amount of items to pay is Rs220

🔐 Limitations & Future Improvements
.✅ Currently supports a maximum of 2 items per order
.📦 Could be extended to support unlimited items using loops/lists
.💾 No data persistence or file/database logging
.📱 No GUI — strictly command-line based

📜 License
This project is provided for educational and demonstration purposes.
