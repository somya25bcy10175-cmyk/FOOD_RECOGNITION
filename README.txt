# 💰 Simple Console Expense Tracker (Python)

## ✨ Overview

The **Simple Console Expense Tracker** is a minimal, command-line application built with Python. Its purpose is to provide users with a fast, non-GUI way to track their personal income and expenditures in real-time. All data is managed in-memory, making it ideal for quick daily tracking sessions without requiring a database setup.

**Key Goal:** Provide clear financial summaries and expense breakdowns directly in the terminal.

## 🚀 Features

* **In-Memory Storage:** Quick data handling without external database dependencies.
* **Transaction Types:** Supports logging both **Expenses** and **Income**.
* **Predefined Categories:** Uses fixed categories (e.g., Food, Rent, Utilities) for quick classification.
* **Financial Summary:** Calculates and displays **Total Income, Total Expenses, and Net Balance**.
* **Category Breakdown:** Generates a report showing spending distribution by category, similar to a pie chart. 

[Image of a Pie Chart showing expense distribution by category]


## 🛠️ Tech Stack

| Component | Technology | Rationale |
| :--- | :--- | :--- |
| **Language** | **Python 3** | Simplicity, readability, and speed for console applications. |
| **Libraries** | **`datetime`** | Standard library module used for timestamping transactions. |
| **Data Storage**| **List of Dictionaries** | Used for in-memory storage, demonstrating core data modeling. |

## 📦 Getting Started

### Prerequisites

* Python 3.x installed on your system.

### Installation & Execution

1.  **Clone or Download:**
    Download the `tracker.py` file or clone this repository:
    ```bash
    git clone [Your Repository URL Here]
    cd simple-expense-tracker
    ```
2.  **Run the Script:**
    Execute the Python file directly from your terminal:
    ```bash
    python tracker.py
    ```

## 💻 Usage Guide

Once the script starts, you will see the main menu. Follow the numbered prompts to interact with the tracker.
### Example Flow

1.  **Record Income (Choice 2):**
    * Enter amount: `2500`
    * Enter category: `Income`
2.  **Record Expense (Choice 1):**
    * Enter amount: `50.50`
    * Enter category: `Food`
3.  **View Summary (Choice 3):**
    * Will display your current net balance.

### Data Note

**Important:** Since this tracker uses in-memory storage, all recorded transactions will be lost when you select **Exit** (Choice 5) or close the terminal window. To persist data, the code would need to be expanded to write to a file (like CSV or JSON) or connect to a database (like SQLite).

## 🤝 Contribution

Feel free to fork this project and add features such as:
* Saving/loading data to a file.
* Deleting or editing transactions.
* Adding more advanced reporting (e.g., monthly comparison).

## 📜 License
