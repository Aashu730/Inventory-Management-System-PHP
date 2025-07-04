# Inventory-Management-System-PHP
A 6-week internship project built with PHP, MySQL, and Chart.js
# Inventory Management System (PHP & MySQL)

A professional Inventory Management System developed during a 6-week IT internship project.  
Built using PHP, MySQL, HTML, CSS, and Chart.js — with a clean, responsive dashboard and modern UI.

---

## 🚀 Features

- ✅ Secure login system
- ➕ Add item with quantity
- 📋 View all items in inventory
- ⚠️ Low stock alert (quantity ≤ 5)
- 📊 Dynamic stock chart using Chart.js
- 💳 Payment demo page
- 🚪 Logout functionality
- 🖼️ Office desk themed dashboard UI (desk.jpg)
- 🔒 MySQL backend with session-based authentication

---

## 🛠 Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Charting**: Chart.js
- **Server**: Hosted on InfinityFree

---

## 📂 Folder Structure
## 🧪 How to Run Locally

1. Clone the repo or download as ZIP
2. Set up a local server using XAMPP or upload to a PHP-compatible host
3. Create a MySQL database and import your table:
   ```sql
   CREATE TABLE `items` (
     `id` int(11) NOT NULL AUTO_INCREMENT,
     `name` varchar(100) NOT NULL,
     `quantity` int(11) NOT NULL,
     PRIMARY KEY (`id`)
   );

