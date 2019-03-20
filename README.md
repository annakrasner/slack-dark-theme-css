# slack-dark-theme-css
just hosting some files for a slack dark theme hack.

## How to:

Open the file ssb-interop.js in your Slack installation.
* Windows path: ~\AppData\Local\slack\<your-slack-version>\resources\app.asar.unpacked\src\static\ssb-interop.js
* Mac Path: /Applications/Slack.app/Contents/Resources/app.asar.unpacked/src/static/ssb-interop.js

At the end of the file, paste in the code in ssb-interop-js-addon.js in this repo.

Change the theme by changing the cssPath in the snippet to the link to the raw github file of the theme you want. Right now it's slack-styles-dark-comfy.css.

Css files are subject to change as i mess with this, so fork and host your own instead
