# Homepage
Custom homepage and new tab page for your browser. Can be edited however you want once downloaded. 
**MAKE SURE YOU DOWNLOAD HTML *AND* CSS**

# Setup
- Firefox
- Chrome

## Firefox
### Homepage
To set it up as your homepage (First thing you see when you open Firefox): 
1. Go into `Settings > Home`
2. Select "Custom URLS..." 
3. Set the custom URL to `file:///<path>/homepage.html` replace `<path>` with the path to where you downloaded the HTML file.
4. Simple as that!
### New Tab
Setting it up to open your homepage in a new tab requires a bit more work, but I've made it as easy as possible for you!
1. Download autoconfig.js and autoconfig.cfg from the setup folder up top
2. Place the files in the correct folders
    - Place autoconfig.js into `C:/Program Files/Mozilla Firefox/defaults/pref`
    - Place autoconfig.cfg into `C:/Program Files/Mozilla Firefox/` **MUST BE IN SAME FOLDER AS `firefox.exe`**
3. Open autoconfig.js
4. Replace `<path to HTML>` with the path to the HTML file
5. Make sure everything is all saved and it should just work!
    - if it doesn't work, restart Firefox entirely. If it *still* doesn't work, make sure you followed all the steps correctly. If it truly honestly **still** doesn't work, idk dude.
## Chromium
These instructions *should* work on all Chromium browsers. It definitely works with Chrome, but it hasn't been tested on Opera or Brave and certainly not anything else.
### Homepage
To set it up as your homepage (First thing you see when you open Chrome:)
1. Go to `Settings > On Startup`
2. select "Open specific page or set of pages"
3. Click add a new page and set the URL as `File:///<path>/homepage.html`, replacing `<path>` with the path to where you downloaded the HTML
### New Tab
This requires adding an Extension to your Chromium browser. If that makes you feel uncomfortable, then sorry. I'm sure there's another workaround but I've not successfully figured it out!
1. Download [New Tab Redirect](https://chromewebstore.google.com/detail/new-tab-redirect/icpgjfneehieebagbmdbhnlpiopdcmna) from the Chrome Webstore
2. Set the custom URL to `file:///<path>/Homepage.html` replacing path with the path to your HTML you downloaded
3. Go to `chrome://extensions` to give the new extension a permission
4. Locate the new extension (`New Tab Redirect`) and click the `Details` button
5. Scroll down to "Allow access to file URLs" and turn it on.