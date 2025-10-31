# 🍔Burgger Restaurant Web Application (Django)

A simple **Restaurant E-Commerce Website** built using **Django** that allows users to:
- Browse food items from the menu  
- Add and remove items from the shopping cart  
- View cart details  
- Proceed to checkout and generate a printable bill  

---

## 🖥️ Features

### 🧾 Core Functionalities
- **Menu Page:** Displays all available food items with images, names, and prices.  
- **Add to Cart:** Users can add multiple items with adjustable quantities.  
- **Cart Management:**  
  - View all selected items  
  - Update or remove items from the cart  
  - Automatic total price calculation  
- **Checkout Page:**  
  - Displays a generated bill for all cart items  
  - Shows total amount  
  - Option to print the bill  
  - Clears cart after checkout  

### ⚙️ Technical Details
- Backend: **Django Framework (Python)**  
- Frontend: **HTML5, CSS3, Bootstrap 4**  
- Database: **SQLite (default Django database)**  
- Template Engine: **Django Templates**  
- Session-based cart system (no login required)  

---

# 🍔 Restaurant Web Application (Django)

A simple **Restaurant E-Commerce Website** built using **Django** that allows users to:
- Browse food items from the menu  
- Add and remove items from the shopping cart  
- View cart details  
- Proceed to checkout and generate a printable bill  

---

## 🖥️ Features

### 🧾 Core Functionalities
- **Menu Page:** Displays all available food items with images, names, and prices.  
- **Add to Cart:** Users can add multiple items with adjustable quantities.  
- **Cart Management:**  
  - View all selected items  
  - Update or remove items from the cart  
  - Automatic total price calculation  
- **Checkout Page:**  
  - Displays a generated bill for all cart items  
  - Shows total amount  
  - Option to print the bill  
  - Clears cart after checkout  

### ⚙️ Technical Details
- Backend: **Django Framework (Python)**  
- Frontend: **HTML5, CSS3, Bootstrap 4**  
- Database: **SQLite (default Django database)**  
- Template Engine: **Django Templates**  
- Session-based cart system (no login required)  

---

## 📂 Project Structure

Restaurant_Web_Project/
│
├── Base_App/
│ ├── migrations/
│ ├── static/
│ │ ├── css/
│ │ ├── js/
│ │ └── images/
│ ├── templates/
│ │ ├── base.html
│ │ ├── menu.html
│ │ ├── cart.html
│ │ └── checkout.html
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py
│ ├── urls.py
│ └── views.py
│
├── Resturant/
│ ├── init.py
│ ├── asgi.py
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
│
├── db.sqlite3
├── manage.py
└── README.md


---

## 🚀 How to Run the Project

### 1️⃣ Clone or Download the Project
```bash
git clone https://github.com/your-username/restaurant-web-django.git
cd restaurant-web-django

pip install django

pip -r install requirements

python manage.py migrate

python manage.py runserver

Open in Browser

Visit → http://127.0.0.1:8000/

🧠 Future Enhancements

User based recommendations

Online payment integration (Razorpay/Stripe)

Save order history in the database


👨‍💻 Developers

Parth — Backend & Logic

Saket — Frontend & UI

Shreya — Integration & Presentation



