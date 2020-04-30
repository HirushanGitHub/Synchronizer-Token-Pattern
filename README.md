# Synchronizer-Token-Pattern

<h3>How to setup Synchronized Token Pattern</h3>
First of all download apache wed server and then install it (WAMP/XAMPP for windows, Lamp for Linux).

If you install "WAMP" for windows OS, there is a file in C:drive named "WAMP". There is a folder named "www" in this file. Then place your web app ("WS" folder of the downloaded zip) to the "www" folder. After that start the "WAMP" server after clicking. At this time you can see a WAMP server green colour incon in the right side of the start bar.

If you install "XAMPP" for windows OS there is a file in C:drive named "XAMPP". There is a folder named "htdocs" in this file. Then place your web app into this folder. Next go to "XAMPP" Control Panal and start Apache web server and MySQL.

After doing one of them, open any web browser in your desktop. After that type as "localhost" in the address box.
If you use XAMPP then, access to the "WS" folder in the "htdocs" file and if you use WAMP then, access to the "WS" folder in the "www" folder through the browser.

eg :- (localhost/WS)

<h2>If this is not work ....</h2>
<h4>I have implemented this,using WAMP server.
Access to the GetCSRF.php from browser.Then copy the current URL of the browser in the address box. After that go to "contact.html" code and found the Ajax call(line no: 57). Paste(line no: 59) the coppied URL to the URL ("http://localhost/WS/GetCSRF.php") which is used to access GetCSRF.php.Save the content and run. 
 </h4>

<h3>When above Zipfile is downloaded the name of it is shown as "Synchronizer-Token-Pattern-master". There is a folder named as 
"Synchronizer-Token-Pattern-master" in the zipfile. Copy the "WS" folder which is in the above folder to the "WWW" or "htdocs" folder and
run it</h3>
