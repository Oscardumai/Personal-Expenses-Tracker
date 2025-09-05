# Personal Expenses Tracker

A simple yet powerful Python-based personal expense tracking system built with Jupyter Notebook.

## 📋 Overview

This expense tracker helps you track your monthly spending, categorise expenses, and analyse your budget utilisation. It provides a clear overview of your financial health with detailed breakdowns and visual summaries.

## ✨ Features

- **Monthly Budget Tracking**: Set and monitor your monthly budget
- **Expense Categorisation**: Organise expenses into categories (Housing, Utility, Food, etc.)
- **Necessity Analysis**: Differentiate between necessary and discretionary spending
- **Budget Utilization**: Calculate percentage of budget used
- **Daily Spending Average**: Track average daily expenditure
- **Detailed Reports**: Comprehensive financial summaries with formatted output

## 🛠️ Technologies Used

- **Python 3.11+**
- **Jupyter Notebook**
- **Standard Python Libraries** (no external dependencies)

## 📊 Data Structure

The tracker uses four parallel lists to manage expenses:
- `items`: Names of expense items
- `prices`: Corresponding amounts spent
- `categories`: Expense categories (Housing, Utility, Food, etc.)
- `necessary`: Boolean values indicating necessity

## 🚀 How to Use

1. **Set Your Budget**: Modify the `budget` variable with your monthly budget
2. **Add Expenses**: Update the lists with your expense items, prices, categories, and necessity flags
3. **Run the Notebook**: Execute all cells to generate your expense report
4. **Analyze Results**: Review the detailed breakdown and summary statistics

## 📈 Sample Output

The notebook generates:
- Welcome message with user and budget information
- Detailed expense breakdown with categorisation
- Summary report with starting/ending balances
- Budget utilisation percentage
- Necessary vs discretionary spending analysis
- Daily spending average

## 🔧 Customization

Easily modify:
- User information (`user`, `current_month` variables)
- Currency symbol (`currency` variable)
- Expense categories and items
- Budget amount and tracking period

## 📁 File Structure

