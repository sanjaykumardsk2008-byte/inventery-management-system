# InventoryPro - Inventory Management System

A web-based warehouse inventory management system built to track, manage, and optimize warehouse stock in real time. Designed with a modern, responsive UI and Role-Based Access Control (RBAC).

---

## ✨ Features

- **Home Dashboard:** Hero banner, real-time statistics (Total Items, In Stock, Low Stock with trend percentages), recent activity feed, and quick-action shortcuts.
- **Inventory Management:** Full CRUD operations for stock items, SKU tracking, category filtering, stock-level indicators, and real-time balance updates.
- **Stock In / Stock Out:** Fast modal to receive and dispatch stock with audit history and activity logging.
- **Item Details:** Detailed views with SKU, category, unit pricing, reorder thresholds, supplier contact info, and complete stock movement history.
- **Order Tracking:** Place orders (e.g. `#ORD1042`), automatically deduct stock quantities, and manage order statuses (*Pending*, *Completed*, *Cancelled*).
- **Reports & Analytics:** Interactive data visualizations (Category breakdown bar chart, stock health ratio donut chart, weekly inbound vs outbound area chart), CSV export, and printable audit reports.
- **Settings & RBAC:** Configurable low-stock thresholds, category management, role-based user management (Admin, Warehouse Manager, Staff), and notification preferences.
- **Role-Based Access Control (RBAC):** Switch between Admin, Warehouse Manager, and Staff roles on the fly.

---

## 🛠️ Tech Stack

- **Frontend:** React 18, Vite, React Router v6, Tailwind CSS, Recharts, Lucide React
- **Backend:** Python 3, Django, Django REST Framework, SQLite
- **Security:** JWT authentication ready, Role-Based Access Control (RBAC)

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/sanjaykumardsk2008-byte/inventery-management-system.git
cd inventery-management-system
```

### 2. Frontend Setup
```bash
# Install dependencies
npm install

# Start Vite dev server
npm run dev
```
The application will be available at: `http://localhost:5173/`

### 3. Backend Setup
```bash
cd backend

# Run migrations
python manage.py migrate

# Seed initial database
python seed.py

# Start Django development server
python manage.py runserver
```
The REST API will be available at: `http://localhost:8000/api/`

---

## 📄 License
This project was developed for Sanjay (November 2026).
