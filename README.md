# Hello Laravel - Client-Server Technologies

## 1. Project Title

Hello Laravel - Client-Server Technologies

## 2. Introduction

Laravel is a popular PHP web application framework that follows the Model-View-Controller (MVC) architectural pattern. It provides tools for routing, database management, templating, and application security, making web development faster and more organized.

Client-Server Technologies are important because they explain how clients, such as web browsers, communicate with servers to request and receive information. Understanding this relationship is essential in modern web application development.

The purpose of this project is to install and configure the Laravel development environment, create a basic Laravel application, and demonstrate how a client accesses a Laravel application through a local development server.

## 3. Objectives

* Install PHP and verify its version.
* Install Composer as the PHP dependency manager.
* Install Laravel and create a new Laravel project.
* Install Git for version control.
* Run a Laravel application using `php artisan serve`.
* Customize the Laravel homepage with student information.

## 4. Development Environment

* **Operating System:** Windows 11
* **PHP Version:** 8.2.12
* **Laravel Version:** 12.66.0
* **Composer Version:** 2.10.2
* **Git Version:** 2.55.0.windows.4
* **MySQL Version:** 26.7.0
* **VS Code Version:** 1.133.0

## 5. Installation Steps

1. Install PHP and verify using `php -v`.
2. Install Composer and verify using `composer -V`.
3. Install Laravel and create the `hello-laravel` project.
4. Install Git and verify using `git --version`.
5. Install MySQL and verify using `mysql --version`.
6. Install Visual Studio Code and open the Laravel project.
7. Run `php artisan serve`.
8. Open `http://127.0.0.1:8000` in a browser.
9. Customize the homepage with the required student information.

Screenshots for each step are available in the `screenshots` folder.

## 6. Project Structure

* **app/** - Contains the application's core code, including models and controllers.
* **routes/** - Defines the application's web and console routes.
* **resources/** - Contains Blade views, CSS, and JavaScript files.
* **public/** - Contains the public entry point and assets accessible by the browser.
* **config/** - Stores application configuration files.
* **database/** - Contains migrations, factories, and seeders.

## 7. Problems Encountered

1. PHP initially required configuration in the Windows PATH environment variable.
2. Composer encountered an HTTP 429 error while downloading Laravel dependencies.
3. Laravel initially returned a 500 Internal Server Error because the `.env` file and application key were missing.
4. Laravel reported that the SQLite database file and cache table were missing during cache clearing.

## 8. Solutions

1. PHP was added to the Windows PATH environment variable so that PHP commands could be executed from Command Prompt.
2. The Composer installation was completed by retrying the dependency installation using the source download method.
3. The `.env` file was created from `.env.example`, and an application encryption key was generated using `php artisan key:generate`.
4. The SQLite database file was created and Laravel migrations were run to create the required database tables.

## 9. Screenshots

* **php-version.png** - PHP version verification.
* **composer-version.png** - Composer version verification.
* **laravel-version.png** - Laravel version verification.
* **git-version.png** - Git version verification.
* **mysql-version.png** - MySQL version verification.
* **vscode.png** - Laravel project opened in Visual Studio Code.
* **artisan-serve.png** - Laravel development server running.
* **hello-laravel-homepage.png** - Completed customized homepage.

## 10. Reflection

This activity taught me how to set up and configure a complete Laravel development environment from the beginning. I learned the role of PHP as a server-side programming language, Composer as a PHP dependency manager, Laravel as a PHP framework, MySQL as a relational database, Visual Studio Code as a code editor, and Git as a version control system. I also learned how to create, customize, and run a Laravel project using the Artisan command-line tool.

Throughout the activity, I encountered several challenges during the installation and configuration process. One of the major problems was the HTTP 429 error that occurred while Composer was downloading Laravel dependencies from GitHub. At first, the project could not run properly because some dependencies had not been completely downloaded. I learned that the messages showing packages being synchronized, installed, and generating optimized autoload files indicated that Composer was still completing the installation. I also encountered problems involving the '`.env` file, the SQLite database, and the application encryption key, which resulted in Internal Server Errors. By examining the error messages and logs, I was able to understand what was missing and work through the configuration problems instead of reinstalling the entire project.

Another important thing I learned was how Git helps manage changes in a project. I learned how to initialize a repository, stage files, create commits, and prepare a project for submission to GitHub. I also encountered a Git configuration issue when Git could not identify my user name and email, which helped me understand that Git requires author information before creating commits.

Laravel is important in client-server development because it provides a structured framework for creating web applications. A browser acts as the client and sends requests to the Laravel application running on the server. Laravel processes these requests through routes and other application components before returning a response to the client. This helped me better understand how client-server applications work in practice.

Overall, this activity improved my ability to install, configure, troubleshoot, and manage a web development project. The experience will help me in future software development because I learned not only how to follow installation steps, but also how to read errors, identify their causes, and solve configuration problems independently. It also gave me practical experience with tools that are commonly used in professional web development.

## 11. References

Laravel. (2026). *Laravel documentation*. https://laravel.com/docs

PHP Group. (2026). *PHP documentation*. https://www.php.net/docs.php

Composer. (2026). *Composer documentation*. https://getcomposer.org/doc/

Git. (2026). *Git documentation*. https://git-scm.com/doc
