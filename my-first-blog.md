# <span style="color:#5b3bd3;">How to Install Laravel 11 on Windows</span>

**![Muhammad Umer Shahzad](https://github.com/Umii010/my-blogs/blob/main/logo.jpeg){: style="width:50px; height:50px; border-radius:50%;"}**  
**Muhammad Umer Shahzad**  
*Published on: September 27, 2024*  
*Estimated reading time: 7 minutes*

---

## <span style="color:#0B3749; font-weight:bold;">Introduction</span>

Hi Guys, Welcome to the new blog! In this post, I'm going to discuss how to install **Laravel 11**, the famous PHP framework.

---

## <span style="color:#0B3749; font-weight:bold;">Prerequisites</span>

Before diving into the Laravel installation procedure, make sure that your system meets the following requirements:

- **Windows** operating system (Windows 10 or later recommended)
- **PHP** (version 8.1 or higher)
- **Composer** (the dependency manager for PHP)

---

## <span style="color:#0B3749; font-weight:bold;">Step 1: Install PHP</span>

You can download PHP from here: [https://www.php.net/downloads.php](https://www.php.net/downloads.php).

**Note:** If you are using local server environments like **XAMPP**, **WAMP**, **LAMP**, **MAMP**, or **EasyPHP**, PHP is already installed, so you can skip this step.

To verify that PHP is installed correctly, open **Command Prompt** or **PowerShell** and run:


The output should be like this:

PHP 8.1.12 (cli) (built: Sep 28 2024)



---

## <span style="color:#0B3749; font-weight:bold;">Step 2: Install Composer</span>

Laravel uses Composer to manage dependencies. Download Composer here: [https://getcomposer.org/download/](https://getcomposer.org/download/).

Once Composer is installed, verify using the terminal:

Run the following command:


Output like this:

Composer version 2.4.3 2024-09-27



---

## <span style="color:#0B3749; font-weight:bold;">Step 3: Install Laravel</span>

There are several ways to install Laravel. I will discuss two of them here:

### 1. Use Laravel Installer:

The Laravel Installer is a dedicated tool that simplifies the installation process. To install it:

Open Command Prompt or PowerShell and run:


Ensure Composer’s global directory is added to your PATH environment variable. Typically, it's located at:

C:\Users\YourUsername\AppData\Roaming\Composer\vendor\bin


Run the following command to create a new Laravel project:


This will create a new project in the folder `my-laravel-app`.

### 2. Use Composer (without Laravel Installer):

You can also install Laravel using Composer directly without the installer. This method is more general and works for other PHP packages as well.

Navigate to the directory where you want to install Laravel:

cd path/to/your/directory


Run the following command to install Laravel:
composer create-project --prefer-dist laravel/laravel my-laravel-app



Once the installation is complete, navigate into your project folder:


---

## <span style="color:#0B3749; font-weight:bold;">Step 4: Start the Laravel Development Server</span>

Start the Laravel server using:



This will start the Laravel server at **http://localhost:8000**. Open your browser and visit the URL to see your Laravel app running.

---

## <span style="color:#0B3749; font-weight:bold;">Step 5: Common Issues and Troubleshooting</span>

Here are a few common issues you might encounter and how to resolve them:

- PHP Not Recognized: Ensure PHP is added to your environment variables.
- Composer Not Recognized: Make sure Composer’s global bin directory is added to your PATH.
- Permissions Issues: Run your terminal as Administrator to avoid permission problems.

---

## <span style="color:#0B3749; font-weight:bold;">Step 6: Conclusion</span>

Congratulations! You've successfully installed Laravel 11 on your Windows machine. Now you're ready to build powerful and scalable web applications.

Stay tuned, and happy coding!

