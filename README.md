![Tera Pos](public/images/logo-dark.png)

> This Project is ready for Production. If you find any bug or have any suggestion please create an Issue.

# Local Installation

-   run `git clone https://github.com/FahimAnzamDip/triangle-pos.git`
-   run `composer update `
-   run `npm install`
-   run `npm run dev`
-   copy .env.example to .env
-   run `php artisan key:generate`
-   set up your database in the .env
-   run `php artisan migrate --seed`
-   run `php artisan storage:link`
-   run `php artisan serve`
-   then visit `http://localhost:8000 or http://127.0.0.1:8000`.

> **Important Note:** "Tera Pos" uses Laravel Snappy Package for PDFs. If you are using Linux then no configuration is needed. But in other Operating Systems please refer to [Laravel Snappy Documentation](https://github.com/barryvdh/laravel-snappy).

# Admin Credentials

> Email: admin@test.com || Password: 12345678

## Demo

![Tera Pos](public/images/screenshot.jpg)
**Live Demo:** https://enigmatic-thicket-18156.herokuapp.com

## Tera Pos Features

-   **Products Management & Barcode Printing**
-   **Stock Management**
-   **Make Quotation & Send Via Email**
-   **Purchase Management**
-   **Sale Management**
-   **Purchase & Sale Return Management**
-   **Expense Management**
-   **Customer & Supplier Management**
-   **User Management (Roles & Permissions)**
-   **Product Multiple Images**
-   **Multiple Currency Settings**
-   **System Settings**
-   **Reports**

# License

**[Creative Commons Attribution 4.0 cc-by-4.0](https://creativecommons.org/licenses/by/4.0/)**
