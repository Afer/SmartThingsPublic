# BELKIN WEMO DIMMER SWITCH INTEGRATION

I only set this up while I was trying to get my Wemo dimmer switch working.  It's actually quite simple but the final result took some time to put together so maybe this will help someone down the line:

** My wemo dimmer switch was already set up and configured with the wemo app at this point.  
** I am not sure if that step is necessary or not 

1. Integrate your smartthings account with github
    - Login to [Smartthings](http://graph.api.smartthings.com) and go to My Device Handlers
    - Click Integrate with Github in the top right and follow the instructions.  You should end up creating a repo like this after forking the public repo
    
2. Add Kris2k2's repo to your smartthings account
    - On the My Device Handlers page, click Settings, then Add New Repository.  In the three boxes enter these values:
    owner: Kris2k2
    name: SmartThingsPublic
    branch: master
    
2. Add the device to your device list
    - Click Update From Repo and select SmartThingsPublic.  It may take a moment, but a modal window will pop up.
    - Find Kris2k2 in the list, check the box next to it, check the publish button at the bottem, then click update.
    
3. Add the app to your smart apps
    - Click My Smart Apps at the top.  Perform the same steps as adding a device.
    - Click Update -> find Kris2k2 -> check publish and update.
    
4. Configure the smart app on your phone's smartthings app
    - Open smartthings.  Go to the automation section and find the Smart Apps tab.  
    - Add a smart app -> scroll to the bottom to find My Apps -> Select the new wemo smart app -> find things
    - Your switch should be automatically found by smart things at this point.  Select it once it is found and then it should just work!


# SmartThings Public GitHub Repo

An official list of SmartApps and Device Types from SmartThings.

Here are some links to help you get started coding right away:

* [GitHub-specific Documentation](http://docs.smartthings.com/en/latest/tools-and-ide/github-integration.html)
* [Full Documentation](http://docs.smartthings.com)
* [IDE & Simulator](http://ide.smartthings.com)
* [Community Forums](http://community.smartthings.com)

Follow us on the web:

* Twitter: http://twitter.com/smartthingsdev
* Facebook: http://facebook.com/smartthingsdevelopers
