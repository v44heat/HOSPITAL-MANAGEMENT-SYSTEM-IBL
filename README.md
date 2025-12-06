# HOSPITAL-MANAGEMENT-SYSTEM-IBL

A simple Hospital Management System built with PHP, MySQL and HTML/CSS/JS — allowing management of patients, doctors, appointments, and more via a web interface.
This project was developed as part of an academic requirement for a school assignment For a group work done by;
<i> Vincent Macharia 
<ii> David Oduor
<iii> Yohana Msami
all at the time 2nd years from The Technical Universty Of Kenya.

---

## 🏥 Features

- User authentication (login/logout) for different user roles (admin, doctor, etc.)  
- Patient search and management (add / view / search patient records)  
- Doctor search and management (add / view / search doctor records)  
- Appointment scheduling / searching  
- Basic hospital services management (via pages such as `services.html`)  
- Contact/feedback page (`contact.php`)  
- Responsive UI and clean layout (uses CSS / JS / assets / vendor libs)  

---

## 🛠 Tech Stack

- **Backend:** PHP  
- **Database:** MySQL (SQL script provided: `myhmsdb.sql`)  
- **Frontend:** HTML, CSS, JavaScript  
- **Assets & Libraries:** CSS/JS assets folders + vendor dependencies  


## 🚀 Setup & Installation (Local server)

1. Clone the repository  
   ```bash
   git clone https://github.com/v44heat/HOSPITAL-MANAGEMENT-SYSTEM-IBL.git
   cd HOSPITAL-MANAGEMENT-SYSTEM-IBL
Copy project folder into your web server’s document root (e.g. htdocs/ for XAMPP)

Run your web server (Apache + PHP) and MySQL

Open your DB admin tool (e.g. phpMyAdmin) and import database:

Use the file myhmsdb.sql provided in repo

Open browser and navigate to the project:
http://localhost/<project-folder>/

⚙️ Configuration
Update database credentials (host, username, password, database) in your PHP config (if config file exists)

Make sure PHP version and MySQL are compatible (PHP 7.4+ recommended)

Verify file/folder permissions so that assets, includes, and SQL import work properly

💡 Usage
Admin can log in to use admin panel (to manage doctors, patients, appointments)

Doctors can log in (via doctor-panel) to view or manage their patients / appointments

Patients (or authorized users) can view services, contact form, etc.

Use search functionality to find patients or doctors by name/id

📄 Database
Schema is provided in myhmsdb.sql.

The database stores tables for users/doctors/patients/appointments (or equivalent — inspect SQL file).

Before using the application, ensure the database is imported and the connection details in PHP config match your setup.

🧑‍💻 Contributing
Feel free to improve or expand the project :)

Fork, create a branch, commit & push changes

Suggested enhancements: role-based access control, input validation, enhanced UI, security (hashing passwords), appointment confirmation, etc.

📝 Licence & Author
This project is currently unlicensed / license unspecified.
You may add your preferred licence (e.g. MIT) if you intend to open-source or share.

Author: Vincent Macharia (v44heat) — original repository owner
