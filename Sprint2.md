Statement of Work - Odin VR Phase 2

A document prepared by Rachit Shah(Co-Founder Logicbots) on 1st November 2022

This documentation is to serve as a 'Statement of Work' or SOW for designing & developing the Odin VR desktop app and web app to enhance the functionalities in it according to the requirements mentioned by Dylan.

LogicBots will work with the Jendamark to:


1) When on web app and you click download. Open application.
    
    Problem
    if application is installed open it and run download simulation which selected.
    opening desktop app using hotlinks/applink with parameters to open that specific simulation.
    
    Possible Solution
    Creating Custom URI for tiggering our deskstop application
	
    Time
    2 weeks
    
	Budget - 700$
	
2) Create a remember me for desktop application
    
    Problem
    
    Remember me on the basis of token
    
    Possible Solution
    
    https://github.com/jaredhanson/passport-remember-me/tree/master/examples/login
    https://github.com/mdarveau/session-rememberme
    
    Time
    1 Week
	
    Budget - 500$
	
3) Update system for both simulation and application

    Problem
    
    -- for new version or changes of application, notify user through web app and desktop app
    Push Notification for web and deskstop version.
    
    Possible Solution
    
    Will have to trigger this from backend. Client app will have to regularly check for updates and provide notification to update. There should be option to push the update region wise. We can also directly build our desktop application when we release/push our code to github.
    https://medium.com/jspoint/packaging-and-distributing-electron-applications-using-electron-builder-311fc55178d9
   
	
4) when clicking the close (X) button it should ask user if to close or minimise the app.
    
    Problem
    
    While pressing close button app should not close directly
    
    Possible Solution
    
    We can ask user to minimize or we can directly minimize the app in the bottom right app drawer. User can directly close our application from app drawer by click RMB > Exit app.
    
	Time(3 & 4)  - 1 Week
  
	Budget(3 & 4) - 400$
