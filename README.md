# ACS Tracker
A Tampermonkey script designed to track the detailed submission status on ACS Publishing Platform.

## Installation
1. **Install Tampermonkey**:  
   - Chrome: Install [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) from Chrome Web Store.  
   - Firefox: Install [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) or [Tampermonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/).  
   - Edge: Install [Tampermonkey](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd).  

2. **Enable Developer Mode for the Extension**
    - For Chrome: Go to `chrome://extensions/`, enable "Developer mode" in the top right corner.  
    - For Firefox: Go to `about:addons`, click on the gear icon, and select "Debug Add-ons".  
    - For Edge: Go to `edge://extensions/`, enable "Developer mode" in the top right corner.

3. **Install ACS Tracker Script**:  
   Click [here](https://github.com/zhangkaihua88/ACS-Tracker/raw/refs/heads/main/acsTracker.user.js) to download the script, or directly install it from the [GreasyFork](https://greasyfork.org/zh-CN/scripts/539931-acs-tracker) listing.


## Usage Guide
1. **Access Manuscript Detail Page**:  
   Navigate to the manuscript page with a URL pattern like `https://publish.acs.org/app/manuscript?*` (e.g., `https://publish.acs.org/app/manuscript?id=123456`) in the ACS Publishing system.  

2. **View Tracking Table**:  
   A detailed status table will automatically appear on the page, displaying:  
   ![](img/acs-tracker-table.png)


 
*ACS Tracker is not affiliated with or endorsed by the American Chemical Society (ACS). Use at your own risk.*