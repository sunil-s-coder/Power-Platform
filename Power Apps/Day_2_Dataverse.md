# Project: Expense Tracker — Table Design

This activity focuses on building the **data layer (“brain”)** of your app using **Dataverse Tables** in the Power Apps Maker Portal.

---

## Step 1: Create the Table

| Setting | Value |
|--------|-------|
| Location | Tables → New table → Table |
| Display Name | **Expense Report** |
| Primary Column | Rename **Name** → **Expense Title** |
| Purpose | Serves as the unique identifier for each expense record |

---

## Step 2: Define Your Columns (Data Types)

Add the following columns to capture structured expense data and understand how Power Apps models information.

| Column Name | Data Type | Purpose |
|------------|-----------|---------|
| Category | Choice | Travel, Meals, Hardware, Software |
| Amount | Currency | Handles decimals and currency symbols correctly |
| Receipt Date | Date only | Captures the date of the expense |
| Status | Choice | Default: Pending; Other values: Approved, Rejected |
| Receipt Image | File (Image) | Allows users to upload or capture receipt photos |
| Manager Comments | Text (Multiple lines) | Enables reviewers to add notes during approval |

---

## Step 3: Using Copilot (The 2025 Way)

Instead of manually adding each column, use the **Copilot pane** on the right side of the Table editor.

**Prompts to try:**
- `Add a column for 'Merchant Name' as a text field`
- `Add a choice column for 'Priority' with Low, Medium, and High`

**Result:**  
Copilot automatically creates the columns and assigns the correct data types.

---

## Step 4: Create a Relationship (Advanced Data)

Build a relational structure by linking expenses to departments.

1. Create a second table named **Departments**
   - Example values: Marketing, Sales, IT
2. Open the **Expense Report** table
3. Add **New column → Lookup**
4. Target Table: **Departments**

**Result:**  
Each expense is now associated with a department, enabling relational data modeling.

---

## Step 5: Add Sample Data

Populate the table with test data to simplify UI design and testing.

1. Click **Edit** in the table toolbar
2. Add at least 2–3 sample records  
   - Example: *Team Lunch*, *$50*, *Meals*, *Pending*

---

## Day 2 — Mastery Checklist

- [ ] At least 5 columns with different data types
- [ ] Lookup column connecting two tables
- [ ] Minimum of 3 rows of sample data
