# SkinGlow ✨

Skin Glow is a skin care online shop that provides users with the ability to view skin care products, register, log-in, edit profile, and purchase. Furthermore, provide the admins with main management options (add, delete, and view user's messages).

This website has been developed using PHP, HTML5, CSS, MySQL for the database (phpmyAdmin), and JavaScript with a main aim to be able to perform security testing against a known SQLi attack vulnerability 👁💉

`NOTE : This Web Application require PHP, JavaScript, HTML5, CSS, and PHPmyAdmin Setups`

To run this web application you need to perform some modification in /config/config.php :

  ```
  define('ROOT_URL', 'http://localhost/skinglow/'); // Add your localhost link to ROOT page "Home page"
  define('DB_HOST', 'localhost');
  define('DB_USER', '');                            // Add your name in phpmyAdmin
  define('DB_PASS', '');                            // Add your password in phpmyAdmin
  define('DB_NAME', '');                    // Add Database name in phpmyAdmin
  
  ```
  
To safeguard this web application, security countermeasures has been applied on both, server-side and client-side, such as : 

-> Handling the user inputs through Input Validation and Sanitization 
-> Secure Data Storage (using Hashing Algorithms)
-> HTML Attribute 
-> Prepared Statements 
-> Characters Escaping 
