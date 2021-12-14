# SUST Online Store
An online store using MySQL, Php and Bootstrap.

Video Presentation: [Drive Link](https://drive.google.com/file/d/15txd2_mQFIL0PeoLq_LcXSgzLs1ZJLQg/view?usp=sharing)

## Prerequisites
1. Install XAMPP web server
2. Any Editor (Preferably VS Code or Sublime Text)
3. Any web browser with latest version

## Languages and technologies used
1. HTML5/CSS3
2. JavaScript (to create dynamically updating content)
3. Bootstrap (An HTML, CSS, and JS library)
4. XAMPP (A web server by Apache Friends)
5. PHP
6. MySQL (An RDBMS that uses SQL)

## Steps to run the project in your machine
1. Download and install XAMPP in your machine
2. Clone or download the repository
3. Extract all the files and move it to the 'htdocs' folder of your XAMPP directory.
4. Start the Apache and Mysql in your XAMPP control panel.
5. Open your web browser and type 'localhost/phpmyadmin'
6. In phpmyadmin page, create a new database from the left panel and name it as 'onlinestore'
7. Import the file 'shopdb.sql' inside your newly created database and click ok.
8. Open a new tab and type 'localhost/foldername' in the url of your browser. That's it.

### Softwares used
  - XAMPP was installed on the Ubuntu 20.04 LTS machine and APACHE2 Server and MySQL were initialized. And, files were built inside opt/lampp/htdocs/myhmsp
  -  Visual Studio Code was used as a text editor.
  - Google Chrome Version 96.0.4664.93 was used to run the project (localhost/sust-shopping was used as the url).

## Features
1. User can view product description, image and other details.
2. Sort products by categories (example: Men/Women or HP/Samsung).
3. Pay online for the products.


There are two modules. 
1. User Module
2. Admin Module

The user enters the website and registers for a new account. The user can then login with proper credentials.
![Login Page](https://user-images.githubusercontent.com/16661968/145960258-92cb22e6-93a5-4c69-82f8-4e249bce7df3.png)

The homepage features new deals and exciting new products.
![homepage](https://user-images.githubusercontent.com/16661968/145960689-88efe198-3d1f-4a74-959c-cb3d7a4685d1.png)

The hompage also contains top-selling products of current month.
![top-selling](https://user-images.githubusercontent.com/16661968/145960806-ed328ee6-1e63-4f66-9f90-85854e6b539d.png)

Clicking on any product will take the user to that product's description page, where the user can view ratings and reviews from other users of that product.
![product_desc](https://user-images.githubusercontent.com/16661968/145961056-a1303ecc-35b7-4078-9979-aed74d31864f.png)

After adding the product to cart, the user can complete the payment procedure from this website.
![cart](https://user-images.githubusercontent.com/16661968/145961358-86da31eb-6b4b-4e77-ad3b-8749c90262de.png)

The admin can add/remove any user. Admin can also add/remove any product.
![admin](https://user-images.githubusercontent.com/16661968/145961491-550a1761-c4e2-48c7-9c0f-ace04d38519d.png)
