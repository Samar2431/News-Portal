📰 News Portal

📌 Overview

The News Portal is a dynamic web application built with PHP & MySQL.
It allows admins to publish and manage news articles while users can browse categories, search, and read details.

---

⚙ Tech Stack

Frontend: HTML, CSS, JavaScript, Bootstrap

Backend: PHP

Database: MySQL (newsportal.sql)

Other Tools: Gulp, jQuery, Plugins

---

📂 Features

🧑‍💻 User Side

Browse news by categories

Read full news details

Search functionality

About & Contact pages


🔑 Admin Side

Secure admin login

Manage categories

Add, edit, and delete news articles

Upload and manage images
---

🛠 Installation & Setup

1. Clone the repository

git clone https://github.com/your-username/newsportal.git
cd newsportal

2. Setup Database

1. Create a new database in MySQL (e.g., newsportal).


2. Import the SQL file:

mysql -u root -p newsportal < newsportal.sql


3. Update database credentials in includes/config.php (or equivalent file).



3. Run Locally

Place the project folder inside your web server’s root directory:

XAMPP: htdocs/newsportal

WAMP: www/newsportal


Start Apache & MySQL.

Open browser:

http://localhost/newsportal


4. Access Admin Panel

Navigate to:

http://localhost/newsportal/admin

Default login (if provided in SQL or docs). Otherwise, create directly in DB.
---

🚀 Future Improvements

Add user authentication & comments

Support multiple languages

Enhance UI with a modern frontend framework
---
🙌 Contributions

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.
