# English-homework
In this task I am describing the operation of the code called "celeste"

# 🛒 Celeste's Store — Product Registration System

A simple command-line application written in Python that allows registering products with their quantities and costs, and calculates the total value of inventory.

---

## 📋 Description

This script simulates a basic store product management system. The user can interactively register products, enter quantities and unit costs, and view a summary with total costs calculated automatically.

---

## ⚙️ Features

- Interactive text menu in the console
- Registration of multiple products in a single session
- Storage of products, quantities, and costs in separate lists
- Automatic calculation of total cost per product (quantity × unit cost)
- Option to continue or stop registering products at any time

---

## 🚀 How to Run

Make sure you have **Python 3** installed.

```bash
python celeste_store.py
```

---

## 🖥️ Usage

When the program starts, a menu with two options appears:

```
Welcome to Celeste's Store
Choose your option:
1. Product registration
2. Bye bye litle bitch
```

Selecting option `1` starts the product registration flow:

```
────product 1─────
Enter product: Apple
Enter quantity: 5
Enter the product cost: 1.50
do you want to continue? yes/no: no
```

If you answer `no`, the registered product list, quantities, and total costs will be displayed.

---

## 📂 Project Structure

```
celeste_store.py 
README.md          
```

## 🧰 Requirements

- Python 3.x
 No external libraries required