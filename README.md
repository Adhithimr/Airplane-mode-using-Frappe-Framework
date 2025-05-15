# ✈ Airplane Mode – Frappe App

Airplane Mode is a custom Frappe application designed to manage airplane ticket bookings, passenger details, and flight-related add-ons. This app demonstrates the use of custom DocTypes, child tables, and RESTful API integrations in the Frappe Framework.

---

## 🔧 Features
- **Airplane Ticket Booking**
  - Passenger details
  - Source and destination airports
  - Flight and timing info
  - Dynamic pricing

- **Add-ons (Child Table)**
  - Extra luggage
  - Meal options
  - Special services

- **API Endpoints**
  - `create_passenger()` - Create a new passenger with details
  - `create_ticket()` – Create a new ticket with full flight details and add-ons
  - `get_all_airlines()` – Fetch all registered airlines
  - `get_all_airplanes()` – List all airplanes

---

## 🚀 Getting Started

### Prerequisites

- Frappe Bench (v13+ recommended)
- Python 3.10+
- Redis, Node.js, Yarn, MariaDB

### Installation

1. Clone the repository inside your Frappe bench:
   ```bash
   cd frappe-bench/apps
   git clone https://github.com/Adhithimr/Airplane-mode-using-Frappe-Framework.git airplane_mode
