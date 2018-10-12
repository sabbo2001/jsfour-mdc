Translate
Turn off instant translation
4031/5000
# jsfour-mdc

Mobile Data Computer, a police station located in all police cars where you can do the following:

(NOTE: Check out the pictures at the bottom for easier understanding)

* Search for people via social security number
  - Here you can see if a person is wanted and its criminal record, even some basic information. It retrieves criminal inforamtion from my criminal record script
* Search for cars via registration number
  - Here you see who owns the car, if the car has received any remarks on previous checks and whether it is inspected
* Write incidents
  - Here you can write down different events that occur in a crime to later create a request so colleagues know why the person is wanted
* Requests
  - Here you can see all the people who are wanted and submit requests
* DNA
  - For those using my DNA script, you can now upload DNA through this computer. For those who do not use it, do not ignore that feature.
* Rules
  - Most of the stuff, but may be nice if the police have to check out any teams

### LICENSE
You are more than welcome to change what you want in the script but you should NOT resell the script or reload it again, refer the people here instead.

### INSTALLATION
For the script to work, you need to use ESX.

* Run the SQL file
* Add load pointers to the users and characters tables, <a href="https://github.com/jonassvensson4/jsfour-register"> jsfour registry <a/> has an SQL file you can run
  - You must have a script, alternatively, load the last word yourself to all users as the script requires this. You can also use my jsfour registry
* If you do not use my <a href="https://github.com/jonassvensson4/jsfourbrottsregister"> jsfour crime register <a/> you will probably get an error, recommend using it. Alternatively, change to server.lua
* If you have added your own police cars then you must add the model name to config.lua
* Add all police in html / assets / js / passwords.js. It says what is needed there. In case of recruitment, the script must be restarted. Alternatively, that person will be able to use another password permanently
* If you have the latest version of esx_vehicleshop then you must replace the original files with those contained in the optional folder
  
### GUIDE
* To open the computer, the police car must be stationary, then click Y
* To remove a remark on the car or any of the criminal records, click on the line you want to delete. Below is the Test (2018-08-10) in the Criminal Record and Fort Running (2018-07-30). That's what you can click on, they are removed from the database
* There is a loss in the menu that does not all see. The "logbook" only lists those who have admin rights in html / assets / js / passwords.js. All logs will be logged. It says who took it away and what was taken away
* The minus sign under PERSONAL INFO when requested will remove the enrollment if the person is requested. It also disappears even if you remove the enlightenment from the backlight tab
* If you want to call someone but you do not have information about a person eg the person number you can write your unknown, unknown or unknown instead
* There is a row named under FORDONSINFO. Currently, that row does not change. It will always be YES on all cars. It is planned that there will be a script for this as this is nothing that the police should be able to change
* Do you want to add layers to the REGELWORK, so do it in html / assets / js / regelverk.js

### Screenshot
[Screenshot] (https://i.gyazo.com/f1686551d68855578946b48b3dce6be7.png)
[Screenshot] (https://i.gyazo.com/dbd27b12f6df5ad8784ddd63eb23afdc.png)
[Screenshot] (https://i.gyazo.com/3859cdd56e2be8a5a18c8ea4f4c0a2d7.png)
[Screenshot] (https://i.gyazo.com/45614bc6e29e50e2ee136f7e68d7ec27.png)
[Screenshot] (https://i.gyazo.com/b60e73635bd1aa7c2af55527d3e0c724.png)
[Screenshot] (https://i.gyazo.com/98fb97ef1ce1d706b710862f899cad3e.png)
