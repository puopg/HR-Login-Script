# HR-Login-Script
This is a series of userscripts that run on specific web pages that must be added via tampermonkey (chrome extension). These extensions are required to run our custom javascript on webpages. It's primary purpose is to automate the login and "ready up" process for Hack Reactor students every morning such that a student will simply access http://www.bookstrap.hackreactor.com or any other site within the HR domain and the login will occur only if needed. 

I encourage our cohort to make pull requests if they have improvements or even suggestions for a better way to do this.

# Pull Requests
- Please say what file you are changing and remember to export the new .zip. Tampermonkey has some issues importing files from my experience, but the .zip works fine. 
- Please update the version # in the file you are changing. (look for the @version tag)

# Installation
These scripts simply need to be added to an extension which allows custom javascript to be ran on a webpage.
If you run into issues importing, always remember you can simply add a new script and copy-paste the contents.

Requirements:
- Github credentials stored in browser
- Install the Chrome extension Tampermonkey 
- Import each script into Tampermonkey

![alt tag](/images/extensionButton.png)
This is what the extension looks like when installed.
You can click dashboard to get to the menu of Tampermonkey.  
<br />
  
![alt tag](/images/importFiles.png)
This is where you will import the .zip.  
<br />

![alt tag](/images/importExample.png)
And this is where you will confirm the import. For scripts with the same name, a version # will appear and it will tell you what type of install/reinstall it is doing. 
<br />

![alt tag](/images/activeScripts.png)
The green dot signifies the script is active. Click to toggle.
<br />

# Things to Refactor (if possible)
- Support for other browsers
- jQuery calls to be less explicit 
- Automatically install the chrome extension and import each script
- Combine all scripts into 1
- Remove the scripts all together
