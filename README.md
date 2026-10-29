# Pharmacy Management & Sales System

A mini project developed using **Python and MySQL** to manage pharmacy operations, including customer records, medicine details, medicine categories, and sales transactions.

## 📁 Project Structure

```text
PharmacyManagementSystem/
│
├── database/
│   ├── schema.sql
│   └── sample_data.sql
│
├── app/
│   ├── db_connection.py
│   ├── customer.py
│   ├── category.py
│   ├── medicine_form.py
│   ├── medicine.py
│   └── sales.py
│
├── main.py
├── requirements.txt
└── README.md
```

## 📌 Folder and File Description

| File/Folder | Description |
|---|---|
| `database/` | Contains SQL scripts for database setup. |
| `schema.sql` | Creates the database tables, primary keys, and foreign keys. |
| `sample_data.sql` | Inserts sample records for testing. |
| `app/` | Contains Python modules for different operations. |
| `db_connection.py` | Establishes the connection between Python and MySQL. |
| `customer.py` | Manages customer records. |
| `category.py` | Manages medicine categories. |
| `medicine_form.py` | Manages medicine forms such as tablets, syrups, creams, and solutions. |
| `medicine.py` | Manages medicine details, prices, expiry dates, and availability. |
| `sales.py` | Records sales transactions and calculates bills. |
| `main.py` | Provides the main menu and integrates all modules. |
| `requirements.txt` | Lists the required Python packages. |
| `README.md` | Provides project documentation and setup instructions. |

## 🗄️ Database Tables

The project uses five tables:

1. **customers** — Stores customer information.
2. **category** — Stores medicine categories.
3. **medicine_form** — Stores medicine forms.
4. **medicine** — Stores medicine details and pricing.
5. **sales** — Stores sales transactions.

## 🛠️ Technologies Used

- Python
- MySQL
- MySQL Connector for Python
- SQL

## ⚙️ Planned Features

- Add, view, update, and search customer records.
- Manage medicine categories and forms.
- Add and search medicines.
- Track medicine prices and expiry dates.
- Record sales and calculate bills.
- Retrieve sales records from the database.
