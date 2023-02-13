Statement of Work - Odin VR Phase 3

A document prepared by Rachit Shah(Co-Founder Logicbots) on 12th Feb 2023

This documentation is to serve as a 'Statement of Work' or SOW for designing & developing the Odin VR desktop app and web app to enhance the functionalities in it according to the requirements mentioned by Dylan.

LogicBots will work with the Jendamark to:


1) Remember me Function
    
    Problem
   User should be able to save the credentials in desktop app using remember me checkbox
    
    Possible Solution
    saving the credentials in local storage and check for it every time user login and autofile the credentials 
	 https://github.com/jaredhanson/passport-remember-me/tree/master/examples/login
    https://github.com/mdarveau/session-rememberme
    
    Time
    3 days 
    
	Budget - 200$
	
2) Update system for both simulation and application

    Problem
    
    -- for new version or changes of application and simulations, notify user through web app and desktop app
    Push Notification for web and deskstop version.
    
    Possible Solution
    
    Will have to trigger this from backend. Client app will have to regularly check for updates and provide notification to update. 
    There should be option to push the update region wise. We can also directly build our desktop application when we release/push our code to github.
    https://medium.com/jspoint/packaging-and-distributing-electron-applications-using-electron-builder-311fc55178d9
    
    For Simulation
   -  Version Column in simulation table for each simulation
   -  On loading dashboard sims, we will check the current version of sims in user system and on the table
   -  If there is a difference we will show user to update the apps or enforce before playing.
   -  New file will be downloaded from s3, and replace the current sim files.
   -  Versioning of sims in S3.
   - Maintain version locally also to compare.
   -  Upload sim should work for both new and updated sims accordingly.
   
   Time - 2 Weeks
  
	Budget - 800$
	
3) Link steamVR and have steamvr automatically download and install with the application
    
    Problem
    
    check vr headsets while playing simulation using steamVR
    
    Possible Solution
    
    - add steam vr package in installation file
    - add folder in resources
    - run steam startup file whenver user login in application
    
    Time - 3-4 days
    Budget - 200$
    
4) Open all 360 videos with SteamVR media player

     Problem
    
    open all the mp4 videos in steam media player
    
    Possible Solution
    
    - will get steam package in installation
    - run steam vr startup (already done in 3)
    - use cmd to run the file in steam media player
    - run steam startup file whenver user login in application

    Time - 1 week
    Budget - 400$
    
