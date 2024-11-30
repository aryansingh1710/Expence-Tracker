# Expence-Tracker            <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Expense Tracker</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Expense Tracker</h1>
    <div class="balance">
      <h3>Your Balance</h3>
      <h2 id="balance">$0.00</h2>
    </div>
    <div class="income-expense">
      <div>
        <h3>Income</h3>
        <p id="income" class="money plus">$0.00</p>
      </div>
      <div>
        <h3>Expense</h3>
        <p id="expense" class="money minus">$0.00</p>
      </div>
    </div>
    <div class="transaction-history">
      <h3>Transaction History</h3>
      <ul id="transaction-list" class="list"></ul>
    </div>
    <div class="add-transaction">
      <h3>Add New Transaction</h3>
      <form id="transaction-form">
        <label for="text">Description</label>
        <input type="text" id="text" placeholder="Enter description..." required>
        <label for="amount">Amount <small>(negative for expense, positive for income)</small></label>
        <input type="number" id="amount" placeholder="Enter amount..." required>
        <button type="submit">Add Transaction</button>
      </form>
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>
