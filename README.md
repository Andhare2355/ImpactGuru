# 🚀 Impact🚀 Impact Guru CRM System
A robust Customer Relationship Management (CRM) system built with Laravel 11. This application manages users, roles, and customers with a clean, responsive interface.

🌟 Features
1. Authentication & Security
Secure Login/Registration using Laravel Breeze.
Role-Based Access Control (RBAC):
Admin: Full access to all modules.
Staff: Restricted access (customizable).
Middleware Protection: unauthorized users are blocked from Admin areas.
2. Customer Management (CRUD)
Create: Add new customers with Name, Email, Phone, and Profile Image.
Read: View a paginated list of customers with search capabilities.
Update: Edit customer details and update profile images.
Delete: Remove customers safely with confirmation prompts.
Image Handling: Uploads are validated and stored efficiently in the public folder.
3. Tech Stack
Framework: Laravel 11
Language: PHP 8.2+
Database: MySQL
Frontend: Blade Templates + Tailwind CSS
Server: Laragon (Apache/Nginx)
🛠️ Installation Guide
Follow these steps to set up the project locally:

1. Clone the Repository
git clone https://github.com/Andhare2355/ImpactGuru/blob/main/README.md

Install Dependencies
composer install npm install npm run build

Environment Setup Rename the example environment file and generate the key:
Bash

cp .env.example .env php artisan key:generate 4. Database Setup Create a database named impact_guru_crm (or your preferred name) in MySQL/HeidiSQL.

Update your .env file:

Ini, TOML

DB_DATABASE=impact_guru_crm DB_USERNAME=root DB_PASSWORD= Run migrations to create tables:

Bash

php artisan migrate 5. Create Storage Link (For Images) To make uploaded images visible:

Bash

php artisan storage:link 6. Run the Server Bash

php artisan serve Visit http://127.0.0.1:8000 in your browser.

👤 User Roles & Testing You can register a new account and assign roles in the database (users table).

Role: admin - Access to Admin Dashboard.

Role: staff - Access to Staff DashboardGuru
A robust Customer Relationship Management (CRM) system built with Laravel 11. This application manages users, roles, and customers with a clean, responsive interface.

🌟 Features
1. Authentication & Security
Secure Login/Registration using Laravel Breeze.
Role-Based Access Control (RBAC):
Admin: Full access to all modules.
Staff: Restricted access (customizable).
Middleware Protection: unauthorized users are blocked from Admin areas.
2. Customer Management (CRUD)
Create: Add new customers with Name, Email, Phone, and Profile Image.
Read: View a paginated list of customers with search capabilities.
Update: Edit customer details and update profile images.
Delete: Remove customers safely with confirmation prompts.
Image Handling: Uploads are validated and stored efficiently in the public folder.
3. Tech Stack
Framework: Laravel 11
Language: PHP 8.2+
Database: MySQL
Frontend: Blade Templates + Tailwind CSS
Server: Laragon (Apache/Nginx)
🛠️ Installation Guide
Follow these steps to set up the project locally:

1. Clone the Repository
git clone https://github.com/Andhare2355/ImpactGuru/blob/main/README.md

Install Dependencies
composer install npm install npm run build

Environment Setup Rename the example environment file and generate the key:
Bash

cp .env.example .env php artisan key:generate 4. Database Setup Create a database named impact_guru_crm (or your preferred name) in MySQL/HeidiSQL.

Update your .env file:

Ini, TOML

DB_DATABASE=impact_guru_crm DB_USERNAME=root DB_PASSWORD= Run migrations to create tables:

Bash

php artisan migrate 5. Create Storage Link (For Images) To make uploaded images visible:

Bash

php artisan storage:link 6. Run the Server Bash

php artisan serve Visit http://127.0.0.1:8000 in your browser.

👤 User Roles & Testing You can register a new account and assign roles in the database (users table).

Role: admin - Access to Admin Dashboard.

Role: staff - Access to Staff Dashboard
