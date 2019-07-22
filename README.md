# slack-dark-theme-css
just hosting some files for a slack dark theme hack.

## How to:
FOR 4.x
Follow the instructions here to edit ssb-interop.bundle.js as seen below. 
* Make sure Slack is not running/in the background. Navigate to C:\Users\USERNAME\AppData\Local\slack\app-4.0.0\resources
* Open app.asar as an archive via 7-zip. 7-zip cannot do this normally you will need an extension. I used Asar7z.
* In the archive, navigate to the /dist/ folder
* Search for ssb-interop.bundle.js and open it
* Append the stuff in ssb-interop-js-addon.js in this repo.
* Save the file. 7-Zip will prompt you if you want to update the archive, say yes.
* Close 7-Zip. Reopen Slack. Eyes rejoice.

BELOW ONLY WORKS IN 3.x
Open the file ssb-interop.js in your Slack installation.
* Windows path: ~\AppData\Local\slack\<your-slack-version>\resources\app.asar.unpacked\src\static\ssb-interop.js
* Mac Path: /Applications/Slack.app/Contents/Resources/app.asar.unpacked/src/static/ssb-interop.js

At the end of the file, paste in the code in ssb-interop-js-addon.js in this repo.

Change the theme by changing the cssPath in the snippet to the link to the raw github file of the theme you want. Right now it's la-cour-slack-night-mode.css.

Css files are subject to change as i mess with this, so fork and host your own instead
