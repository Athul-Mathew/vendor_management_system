# vendor_management_system
# Vendor Management System

This Vendor Management System is built using Django and Django REST Framework. It handles vendor profiles, purchase orders, and vendor performance metrics.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Athul-Mathew/vendor_management_system.git
2. Navigate to the project directory:
     cd vendor-management-system
3.Create a virtual environment:
    python -m venv venv
4.Activate the virtual environment:
  .\venv\Scripts\activate
5.Install dependencies:
  pip install -r requirements.txt
6.Apply database migrations:
  python manage.py migrate
7.Create a superuser (admin) account:
  python manage.py createsuperuser
8.Run the development server:
  python manage.py runserver


**API Endpoints***

*Vendor Management*
● POST /api/vendors/: Create a new vendor.
● GET /api/vendors/: List all vendors.
● GET /api/vendors/{vendor_id}/: Retrieve a specific vendor's details.
● PUT /api/vendors/{vendor_id}/: Update a vendor's details.
● DELETE /api/vendors/{vendor_id}/: Delete a vendor.

*Purchase Order Tracking:*
● POST /api/purchase_orders/: Create a purchase order.
● GET /api/purchase_orders/: List all purchase orders with an option to filter by vendor.
● GET /api/purchase_orders/{po_id}/: Retrieve details of a specific purchase order.
● PUT /api/purchase_orders/{po_id}/: Update a purchase order.
● DELETE /api/purchase_orders/{po_id}/: Delete a purchase order.

*Vendor Performance Evaluation:*
GET /api/vendors/{vendor_id}/performance: Retrieve a vendor's performance metrics.

   
