# Holonis Mass Follow Script
 
## DISCLAIMER:
I am not responsible for the clousure or deletion of your account. This script is for learning purposes only, and should not be used in any other way. Be aware that follow scripts like this may be in violation of Holonis' terms of service.

## About
This script will search for and click all elements with the "btn btn-follow-follower" class name, which can only be found in users that you are not following (look for the "follow" button next to someone's name). In other words, this script will click all loaded "follow" buttons on a page, and stop when there are no more "follow" buttons.

This javascript is derived from a Twitter mass follow script found at: 
https://www.warriorforum.com/social-media/932506-twitter-mass-follow-javascript-code.html
- Full credit goes to darkc0de1 for the original script

## Requirements: 
Google Chrome, or any browser with access to the javascript console.

## How to use:
### Step 1: 
Copy the script below:

```
var inputs = document.getElementsByClassName('btn btn-follow-follower'); for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

### Step 2: 
Go to a page on Holonis that has many follow buttons (going to someone's followers, or following page will load many users at once)

### Step 3: 
Press F12 (on Chrome) to access developer tools, and if you are not on the console page already, find the tab that says console and click it

### Step 4: 
Paste the script into the console and hit enter on your keyboard, the script will quickly follow everyone on the page that is loaded (remeber, this looks very obvious to the Holonis team).

## Closing Note
Once again, I am not responsible for any consequences that may come to your account. Holonis have made it public and clear that scripts like these are very obvious to developers because of the shear volume of follows done in such a short succession of time. The intent of me posting this is for others to learn how easy a mass follow script can be to create and use. Thank you!
