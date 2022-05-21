# SkinGlow ✨

Skin Glow is an online skincare shop that provides users with the ability to view skincare products, register, log in, and purchase. Furthermore, give the admin's main management tasks (delete, add, and view user's messages).

This website has been developed using `PHP, HTML5, CSS, MySQL for the database (phpMyAdmin), and JavaScript` with a main aim to be able to perform security testing against `SQLi vulnerability `👁💉

`NOTE : This Web Application require PHP, JavaScript, HTML5, CSS, and phpMyAdmin Setups`

To run this web application you need to perform some modification in /config/config.php :

  ```
  define('ROOT_URL', 'http://localhost/skinglow/'); // Add your localhost link to ROOT page "Home page"
  define('DB_HOST', 'localhost');
  define('DB_USER', '');                            // Add your name in phpMyAdmin
  define('DB_PASS', '');                            // Add your password in phpMyAdmin
  define('DB_NAME', '');                    // Add Database name in phpMyAdmin
  
  ```
  
To safeguard this web application, security countermeasures has been applied on both, server-side and client-side, such as : 

  1. Handling the user inputs through Input Validation and Sanitization 
  2. Secure Data Storage (using Hashing Algorithms)
  3. HTML Attributes
  4. Prepared Statements 
  5. Characters Escaping 
