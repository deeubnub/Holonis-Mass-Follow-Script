# Holonis Mass Follow Script
 
# DISCLAIMER:
### I AM NOT RESPONSIBLE FOR THE CLOSURE OR DELETION OF YOUR ACCOUNT, THIS SCRIPT IS FOR LEARNING PURPOSES, USE AT YOUR OWN DESCRETION. FOLLOW SCRIPTS LIKE THIS ONE AND OTHER FORMS OF BOTS MAY VIOLATE HOLONIS' TERMS OF SERVICE.

# About
This script will search for and click all elements with the "btn btn-follow-follower" class name, which can only be found through users that you are not following (look for the "follow" button next to anyone's name). In other words, this script will click every and all loaded "follow" buttons on a page and then stop.

This javascript is derived from a Twitter mass follow script found at: 
https://www.warriorforum.com/social-media/932506-twitter-mass-follow-javascript-code.html
- Full credit goes to darkc0de1 for the original Twitter Mass Follow script

# How to use:
## Requirements: Google Chrome, or any browser with access to the javascript console.

### Step 1: 
Copy the script below:

'''
var inputs = document.getElementsByClassName('btn btn-follow-follower'); for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
'''

### Step 2: 
Go to a page on Holonis that has many follow buttons (going to someone's followers, or following page will load many users at once)

### Step 3: 
Press F12 (on Chrome) to access developer tools, and if you are not on the console page already, find the tab that says console and click it

### Step 4: 
Paste the script into the console and hit enter on your keyboard, the script will quickly follow everyone on the page that is loaded (remeber, this looks very obvious to the Holonis team).

# Closing Note
Once again, I am not responsible for any consequences that may come to your account. Holonis have made it public and clear that scripts like these are very obvious to developers because of the shear volume of follows done in such a short succession of time. The intent of me posting this is for others to learn how easy a mass follow script can be to create and use. Thank you!
