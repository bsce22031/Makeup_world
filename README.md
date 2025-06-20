# 💄 Makeup World – PHP-Based Web Application
Makeup World is a simple PHP-based web application that allows admin users to manage makeup products through a CRUD dashboard. It includes basic authentication and a styled frontend.

# 🌐 Features
🛒 Product Management: Add, update, delete, and view makeup products.

🔐 Admin Login System: Basic login system for admin access.

🎨 Frontend Layout: A landing page (index.html) with product visuals.

📸 Image Gallery: Product images stored locally and displayed on the frontend.

💾 Database Connectivity: PHP + MySQL integration through db.php.

# 📁 Project Structure
pgsql
Copy
Edit
# makeup_website/
│
├── admin_dashboard.php     # Admin product dashboard
├── admin_login.php         # Admin login page
├── create.php              # Add new product
├── db.php                  # Database connection
├── delete.php              # Delete product
├── index.html              # Main landing page
├── logout.php              # Logout functionality
├── products.php            # Product display
├── read.php                # View product details
├── update.php              # Update existing product
├── user_login.php          # Placeholder for user login (future use)
├── validate_admin.php      # Admin login validation
├── style.css               # Stylesheet
└── image/                  # Product image directory
# ⚙️ Setup Instructions
# Clone this repo:

bash
Copy
Edit
git clone https://github.com/yourusername/makeup_website.git
cd makeup_website
# Start a local server (e.g., WAMP, XAMPP, or MAMP):

Place the project folder inside www (for WAMP) or htdocs (for XAMPP).

# Import the Database:

Open phpMyAdmin.

Create a new database (e.g., makeup_db).

Import your SQL file (create one if not included).

# Configure db.php:
Update your database credentials in db.php:

php
Copy
Edit
$conn = mysqli_connect("localhost", "root", "", "makeup_db");
# Run the App:

Visit http://localhost/makeup_website/index.html in your browser.

# 🔒 Admin Login
Username: Maryam

Password: 1234
# 📷 Screenshots
![image](https://github.com/user-attachments/assets/187540c5-5c9c-41fa-ba98-c6bfa553cd8e)
![image](https://github.com/user-attachments/assets/ad99a6e6-5284-4735-bcdf-747a8bcc0549)
![image](https://github.com/user-attachments/assets/fc74f085-4dcf-476f-8565-137d2052840e)
![image](https://github.com/user-attachments/assets/c028a56e-d2d3-40e6-83aa-c8ac436bdb88)
![image](https://github.com/user-attachments/assets/81ae462c-9f51-43bf-ac7e-2402a2565269)

