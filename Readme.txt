Whats up! 

I had alot of fun with this, there's quite abit to it but if you follow along below ill try explain everything.


****************
Project Set-up 
****************

First you need node.js -> https://nodejs.org/en/   (download and install)
	
Everything else you need is in the folder: fitbit-OAuth2

Next edit the config with your FitBit Settings (/fitbit-OAuth2/config/auth.json)
Put in your clientID and ClientSecret, be carefull not to delete any quotes. Also copy callbackURL for next step.

Log into FitBit Dev and edit your application settings to use the callback -> http://localhost:3000/auth/fitbit/callback

Once all that is down the next few steps use the command prompt.
Incase you havent used id ->  https://www.youtube.com/watch?v=VyiGZW0fTxk

next we must change the cmd dictionary to our fitbit-OAuth2 folder. This is done through the cd command.
So for me the command looks like:

cd C:\Users\Shane\Work\Personal\fitbit-OAuth2

Yours will have a different path, all depends on where you download it. 
e.g when the folder is on the Desktop (C:\Users\Shane\Desktop\MyFitbit\fitbit-OAuth2) just replace your name and you are good to go.

Once inside this folder type the command: npm install
Hopefully that will start installing everything else you need but if it looks like its doing nothing gimmie a shout. 

Finnaly run the command: node app.js 
This starts up the node server and runs the app.js on it. 


************
How To use
************

Type: localhost:3000 into your browser.

This should bring up the app. Currently it looks extremely basic but I am going to jazz it up to make it look more modern 
for my own sake. I can send it onto you when im done but for now this is fine to get learning.

Go login -> login with fitbit -> enter your fitbit account -> account 

Thats it really. Looking at the cmd window you will be able to see all the information comming back.

Hitting refresh on the browser sometimes breaks it. To fix this you need to resart the server.
click on the cmd window and hold ctrl and double hit C. this stops the server and allows you to type again. 
Type node app.js to start the server again. 
 


 