# NotesApp
This is a Notes making Online application where you can save all your notes with your account details. 

### Application consists features such as
1. Portals for each user, 
2. Sending an activation key to the user account for account confirmation after registering
3. sessions to continue from where he left
4. cookies to store the user details when he checks remember me in the registration
5. forgot password

### Web Technologies Used:

1. Front End : HTML, CSS, Bootstrap, JQuery, JavaScript
2. Back End : PHP
3. DataBase : MySql

### Few Functions that are used in this Project:

1. mail(receiver, subject, message, header) ---> to send mail
if you want to use this function through local host you may go through this link : https://www.youtube.com/watch?v=4_NP_WYFmIM
2. fiter_var(variable,FILTER_SANITIZE_STRING) ---> to clean the html content from the variable
3. filter_var(variable, VALIDATE_) ANYVARIABLE to validate the email---> if not validated it returns nothing, otherwise it returns the value
4. date() and time() ---> to get data and time in required formats
5. setcookie("name","value","timestamp") --- to set cookie
6. print_r($_COOKIE); ---> global variable to display cookie
7. setcookie("name","", time()-1000); ---> to delete cookie
8. serializeArray()---> to collect user inputs
9. mysqli_real_escape_string() ---> to remove unnecessary things
10. md5(), hash('sha256', $password)--> two meethods for converting password into hashcode
11. mysqli_num_rows() ---> to see number of rows that are available in the table of a database
12. mysqli_error() ---> gives the last executed query
13. bin2hex(openssl_random_pseudo_bytes(16));---> generates activation code and later converts into hexadecimal one 
14. explode(',',variable) ---> splits the value in variable based on the ','
