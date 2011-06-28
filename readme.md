#Instagram Desktop Latest

##About
This is a quick and dirty script that accesses your Instagram feed (you and those you follow) and redirects to the URL for the latest photo. By pointing something like [GeekTool](http://projects.tynsoe.org/en/geektool/) at the page you can have an updating picture on your desktop.

##Requirements
A PHP server (local or remote) and an Instagram account.

##Installation
Edit the file to use your own [self feed URL](http://instagram.com/developer/endpoints/users/) - Instagram handily includes your access token in the documentation when you log in.  
Edit the file to point to an image to use in the case of an error.  
Upload the index.php file to your server.  
If you want to use GeekTool, create a new "image" entry and point it to the URL of where you uploaded the page.