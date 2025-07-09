## 🛍️ Python Shopify Clone (Console App)

This is a **beginner-friendly, terminal-based shopping application** built using core Python. It allows **sellers** to list products and **buyers** to browse and purchase them. All data is stored in simple `.csv` files—no database or external libraries needed.

---

## 🚀 Features

🔸 **Role-based Menus**
 Choose to act as a Seller or a Buyer with separate features for each.

🔸 **Seller Functionalities**

* Add new products (name, price, stock)
* View your listed products

🔸 **Buyer Functionalities**

* Browse all available products
* Buy products (stock updates automatically)
* View your past orders

🔸 **Tabular Terminal Display**

* Cleanly formatted tables using `str.ljust()` for better readability

🔸 **CSV-based Local Storage**

* `products.csv`: Product listings
* `orders.csv`: Buyer orders

---

## 🧱 Folder Structure

```
minishop/
│
├── main.py
├── products.csv     # Auto-created
└── orders.csv       # Auto-created
```

---

## 🐍 Tech Stack

* **Language**: Python 3
* **Storage**: CSV files (no database required)
* **Interface**: Console (text-based)

---

## ▶️ Getting Started

1. **Clone or Download** this repository
2. Run the app:

   ```bash
   python main.py
   ```

---

## 📸 Screenshots

### Product Listing (Tabular View):

```
ID    Seller     Product Name         Price    Stock 
------------------------------------------------------------
1     Alice      Wireless Mouse       ₹699     20    
2     Bob        Bamboo Bottle        ₹249     12    
```


