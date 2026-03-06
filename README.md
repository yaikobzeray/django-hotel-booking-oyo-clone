# 🏨 OYO Clone - Hotel Booking Platform

A high-performance, full-featured hotel booking web application built with **Django**. This project is a comprehensive clone of the popular OYO booking service, featuring dual-role systems for both guests and property vendors.

## 🚀 Key Features
- **Dual Authentication System:** Specialized flows for both guests and hotel vendors.
- **Hotel Listings:** Categorized and searchable database of hotels.
- **Image Gallery:** Seamless hotel image uploads and display.
- **Room Management:** Vendors can handle room availability and pricing details.
- **Booking Flow:** Easy-to-use checkout process for guests.
- **OTP Verification:** Email-based OTP system for secure user verification.
- **Vendor Dashboard:** A powerful management hub for hotel owners to track bookings and properties.

## 🛠️ Built with
- **Backend Architecture:** Python, Django
- **Frontend Interaction:** HTML5, CSS3, JavaScript, Bootstrap
- **Notification System:** OTP-based email utility for safety.
- **Search Logic:** Refined filtering for hotel locations and categories.

## ⚙️ Installation & Operation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yaikobzeray/django-hotel-booking-oyo-clone.git
   cd django-hotel-booking-oyo-clone
   ```

2. **Establish a virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages:**
   ```bash
   pip install django pillow  # Basic setup
   ```

4. **Prepare the database:**
   ```bash
   python manage.py migrate
   ```

5. **Start your local server:**
   ```bash
   python manage.py runserver
   ```

Visit `http://127.0.0.1:8000` to book your first stay!

## 🏨 Vendor Access
- Access the dashboard at `/vendor/dashboard/` after registration as a vendor.
- Upload property images effortlessly!

## 🤝 Contributing
Open for PRs and feature requests. Feel free to fork!

## 📄 License
This project is licensed under the MIT License.
