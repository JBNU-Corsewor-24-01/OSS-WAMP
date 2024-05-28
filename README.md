# OSS-WAMP


# WAMP + WordPress Webpage Serving Project

## Introduction
This project demonstrates how to set up a local web server using WAMP (Windows, Apache, MySQL, PHP) and WordPress to serve a web page. WAMP provides a robust environment for developing and testing websites locally before deploying them to a live server.

## Prerequisites
- A Windows operating system.
- Download and install [WAMP](https://sourceforge.net/projects/wampserver/).
- OR Download here..! [WAMP-MIRROR](http://gofile.me/7nScK/UDIA3cZ8s).
- Download the latest version of [WordPress](https://wordpress.org/download/).

## Installation Guide

### Step 1: Install WAMP
1. Download the WAMP server from the [official website](https://sourceforge.net/projects/wampserver/).
2. Run the installer and follow the on-screen instructions.
3. Once installed, launch WAMP and ensure that the server is running. You should see a green icon in your system tray.

### Step 2: Set Up MySQL Database
1. Open phpMyAdmin by clicking on the WAMP icon in the system tray, then selecting `phpMyAdmin`.
2. Log in with the default credentials (username: `root`, password: leave blank).
3. Create a new database for WordPress. Name it `wordpress`.

### Step 3: Install WordPress
1. Extract the downloaded WordPress zip file into the `www` directory of your WAMP installation (typically `C:\wamp64\www`).
2. Rename the extracted folder to `wordpress`.
3. Open a web browser and navigate to `http://localhost/wordpress`.
4. Follow the on-screen instructions to configure WordPress:
    - Select the language.
    - Enter the database details:
      - Database Name: `wordpress`
      - Username: `root`
      - Password: (leave blank)
      - Database Host: `localhost`
      - Table Prefix: `wp_`
5. Complete the installation by providing the necessary site information and creating an admin account.

## Usage
- To start the server, launch WAMP and ensure the icon in the system tray is green.
- Access your WordPress site by navigating to `http://localhost/wordpress` in your web browser.
- Use the WordPress admin dashboard to customize and manage your website.

## Troubleshooting
- If the WAMP icon is not green, it indicates an issue with the server. Check the Apache and MySQL services to ensure they are running.
- If you encounter database connection errors, verify the database credentials in the `wp-config.php` file located in the `wordpress` directory.

## Conclusion
By following this guide, you should have a fully functional local WordPress site running on WAMP. This setup allows for easy development and testing of WordPress themes and plugins in a controlled environment.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
