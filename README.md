# Cargo & Expedition Logistics Platform 🚚

A robust logistics management web application designed for freight forwarders and cargo carriers to coordinate multi-point route dispatching, airway bill tracking, and high-volume shipment manifests.

---

## 🌟 Live Demo & Portfolio
- **Author:** Frans Kurniawan
- **Portfolio:** [https://franskur.github.io](https://franskur.github.io)
- **Role:** Full-Stack PHP Web Developer

---

## 🚀 Key Features

- **Automated Distance & Weight Tariff Calculator:**
  - Multi-tier volumetric weight and geographic zone matrix calculation for instant freight rate estimation.
  - Surcharge calculations for express handling and special goods classifications.

- **End-to-End Shipment Milestone Tracking:**
  - Complete shipment lifecycle logging: Origin Warehouse Intake $\rightarrow$ Sorting Hub $\rightarrow$ Transit Point $\rightarrow$ Out for Delivery $\rightarrow$ Signed Receipt.
  - Public tracking portal accessible via unique Tracking Number (Airway Bill).

- **Digital Manifest & Waybill Document Issuance:**
  - Automated PDF generation of Airway Bills (AWB), Delivery Orders (DO), Driver Manifests, and Cargo Loading Lists.

- **High-Volume Transactional Query Optimization:**
  - Database schema indexed specifically for rapid lookups and concurrent multi-branch queries.

---

## 🛠️ Tech Stack & Architecture

- **Backend:** PHP Native (OOP, Modular MVC Design)
- **Database:** MySQL (Optimized indexes on tracking codes, timestamps, and origin/destination pairs)
- **Document Engine:** TCPDF / FPDF for automated logistics document generation
- **Frontend:** HTML5, CSS3, JavaScript (ES6+), Bootstrap 5

---

## ⚡ Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/franskur/cargo-logistics-platform.git
   ```

2. **Database Configuration:**
   - Import `database/cargo_db.sql` into MySQL.
   - Configure database credentials in `config/database.php`.

3. **Run Application:**
   ```bash
   php -S localhost:8000 -t public/
   ```

---

## 📄 License & Notes
Designed and developed by **Frans Kurniawan**. Open for portfolio showcase and freight operations.
