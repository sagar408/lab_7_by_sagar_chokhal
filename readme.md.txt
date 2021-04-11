Lab 7 by sagar chokhal 

sessions-An alternative way to make data accessible across the various pages of an entire website is to use a PHP Session.
A session creates a file in a temporary directory on the server where registered session variables and their values are stored. 
This data will be available to all pages on the site during that visit.
The location of the temporary file is determined by a setting in the php.ini file called session.save_path. 
Before using any session variable make sure you have setup this path.

cookies-A cookie is a small file with the maximum size of 4KB that the web server stores on the client computer.
They are typically used to keeping track of information such as a username that the site can retrieve to personalize 
the page when the user visits the website next time.A cookie can only be read from the domain that it has been issued from.
Cookies are usually set in an HTTP header but JavaScript can also set a cookie directly on a browser.