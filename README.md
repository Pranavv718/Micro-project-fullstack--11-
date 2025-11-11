# 🏨 Micro-Project-Fullstack--11-
### Django Hotel Management System

A full-stack **Hotel Management System** built using **Django (Python)** for efficient hotel room booking, customer management, and staff coordination.  
It provides separate modules for customers and administrators, allowing hotel operations to be managed digitally and effectively.

---

## 📘 Project Description

The **Hotel Management System** is a web-based application designed to simplify hotel operations like room booking, customer data management, and availability tracking.  
It uses the **Django framework** for backend logic and the **Bootstrap framework** for a responsive, user-friendly interface.

This system helps both **customers** and **hotel managers**:
- Customers can browse available rooms, check availability by date, and book rooms online.
- Hotel managers (admins) can manage rooms, bookings, and customer data through a secured admin dashboard.

The project demonstrates **full-stack development** concepts — integrating frontend design, backend logic, and database management into a single Django application.

---

## 👨‍💻 Team Members
| Name | USN |
|------|------|
| Pranav Bharadwaj V | 4MC23IS072 |
| Praneeth M | 4MC23IS073 |
| Dhanush Gowda | 4MC23IS030 |
| Nithin H R | 4MC23IS067 |

---

## 🧩 Features

- 🔑 **User Authentication:** Secure login and registration for customers and managers.  
- 🏠 **Room Management:** Add, view, and manage available rooms with details like price and capacity.  
- 📅 **Booking System:** Search and book rooms based on date and room availability.  
- 👨‍💼 **Admin Dashboard:** Manage all hotel data — rooms, customers, and bookings — from one place.  
- 📸 **Image Management:** Upload and display room images (using Pillow library).  
- 📱 **Responsive UI:** Built with Bootstrap for mobile and desktop-friendly design.  
- 🗄️ **Database:** All data stored securely in an SQLite3 database managed via Django ORM.  

---

## 🧱 Tech Stack

| Layer | Technology | Purpose |
|--------|-------------|----------|
| **Frontend** | HTML5, CSS3, Bootstrap 5 | User Interface design and responsiveness |
| **Backend** | Django 3 (Python) | Core logic, authentication, data management |
| **Database** | SQLite3 | Store customer, room, and booking data |
| **Libraries** | Django REST Framework, Pillow | APIs and image handling |
| **Tools** | VS Code, GitHub, venv | Development, version control, and environment management |

---

## ⚙️ Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/Pranavv718/Micro-project-fullstack--11-.git

# 2. Navigate to the project directory
cd Micro-project-fullstack--11-

# 3. Create a virtual environment
python -m venv venv

# 4. Activate the virtual environment
venv\Scripts\activate   # On Windows
source venv/bin/activate  # On macOS/Linux

# 5. Install dependencies
python -m pip install -r requirements.txt

# 6. Run database migrations
cd room_slot
python manage.py migrate

# 7. Create superuser (for admin access)
python manage.py createsuperuser

# 8. Run the development server
python manage.py runserver
