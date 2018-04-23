# Holonis Mass Follow Script
 
## Disclaimer
I am not responsible for the clousure or deletion of your account. This script is for learning purposes. But be aware that mass follow scripts like this may be in violation of Holonis' terms of service. You have been warned.

## About
This script will search for and click all elements with the "btn btn-follow-follower" class name on someone's "followers" page, which can only be found in users that you are not following (look for the "follow" button next to someone's name). In other words, this script will click all loaded "follow" buttons on a "followers" page, and stop when there are no more "follow" buttons to engage with.

This javascript is derived from a Twitter mass follow script by darkc0de1 found at: 
https://www.warriorforum.com/social-media/932506-twitter-mass-follow-javascript-code.html
- Full credit goes to darkc0de1 for the original script

## Requirements 
Google Chrome, or any browser with access to the javascript console.

## How to use
### Step 1: 
Copy the script below:

```
var inputs = document.querySelectorAll("button.btn-follow-follower:not(.following)"); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

### Step 2: 
Go to someone's "followers" page (the page filled with people that a person follows).

### Step 3: 
Press F12 (on Chrome) to access developer tools and, if you are not in the console already, find and click the tab that says console.

### Step 4: 
Paste the script into the console and hit enter on your keyboard, the script will quickly follow everyone on the page that is loaded.

## Closing Note
Once again, I am not responsible for any consequences that may come to your account. Holonis have made it very clear that scripts like this are very obvious to developers because of the shear volume of follows done in such a short succession of time. The intent of me creating this is for others to learn how easy a mass follow script can be to create and use. Thank you!
