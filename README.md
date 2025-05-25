# BookStore
I am Tasbiha Zaman student of PUB 23rd batch BSc in CSE, ID-35. 

Today I’m showing my project titled “Laravel Bookstore Management System.”

🌟 Features

Book CRUD Operations (Create, Read, Update, Delete)

Pagination (10 books per page)

Responsive Design

Modern UI (Bootstrap 5)

🛠️ Technologies Used

Backend: Laravel 12

Frontend: Bootstrap 5

Database: MySQL

Pagination: Laravel Paginator

🚀 Installation

laragon install

composer install

project on folder www

🚀 Run on Terminal

cd book-store
code .

Edit .env file:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=bookstore
DB_USERNAME=root
DB_PASSWORD=

create a database name bookstore

php artisan migrate

php artisan db:seed

php artisan serve

Access the application at http://127.0.0.1:8000

📂 Project Structure

book-store/
├── app/               # Core application logic
    └── Http/          # Controllers
    ├── Models/        # Database models
│   └── Providers/     # Paginator     
├── database/          # Factories, Migrations and seeders
├── resources/         # Views Create books and layout folder and it's file
├── routes/            # Application routes

📝 License
This project is open-source and available under the MIT License.

Thank You!

🔹 Short Video Link: https://youtu.be/aYmCXCZK3uk?si=HnrvRljB5xZnzfY9
