# My Expense Tracker

My Expense Tracker is a React and Redux-based application that helps users manage their expenses effectively. Users can add, view, and delete transactions, manage budgets for specific categories, and track their remaining funds in real-time.

## Features

- **Add Transactions**: Users can add new transactions with details such as category, description, and amount.
- **View Transactions**: Displays a list of all transactions with their details.
- **Delete Transactions**: Allows users to remove transactions from the list.
- **Manage Budgets**: Users can set and edit budgets for specific categories.
- **Track Expenses**: Automatically calculates total expenses for each category.
- **Funds Remaining Indicator**: Displays remaining funds for each category with visual cues (positive or negative).

---

## Components

### Budget Component

The component is a key part of the Expense Tracker App. It allows users to manage their budgets for specific categories, track expenses, and view remaining funds in real-time.

#### Features

- **Edit Budget Amount**: Users can update the budget amount for a specific category.
- **Track Expenses**: Automatically calculates the total expenses for the category.
- **Funds Remaining Indicator**: Displays the remaining funds for the category with visual cues (positive or negative).

---

### Transaction Component

The component is a React functional component used in the application. It is responsible for rendering individual transaction items and providing functionality to delete a transaction.

#### Features

- Displays transaction details including:
  - Amount
  - Category
  - Description
- Provides a delete button to remove a transaction from the list.

---

### Transaction Form Component

The component provides a form for users to add new transactions to the application.

#### Features

- Allows users to input transaction details including:
  - Category
  - Description
  - Amount
- Dispatches an action to add the transaction to the Redux store.
- Resets the form fields after submission.

---

### Transaction List Component

The component is responsible for rendering a list of transactions.

#### Features

- Displays a list of transactions.
- Dynamically renders each transaction.

---

## Technologies Used

- **React**: For building the user interface.
- **Redux**: For state management.
- **UUID**: For generating unique IDs for transactions.
- **CSS**: For styling the components.



## Usage

1. Add a new transaction using the form.
2. View the list of transactions in the transaction list.
3. Delete transactions as needed.
4. Manage budgets for specific categories and track remaining funds.

---

## File Structure

- `src/components/Transaction.js`: Renders individual transactions.
- `src/components/TransactionForm.js`: Provides a form to add new transactions.
- `src/components/TransactionList.js`: Displays a list of transactions.
- `src/components/Budget.js`: Manages budgets and tracks expenses.

---

