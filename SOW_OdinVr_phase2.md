Statement of Work - Odin VR Phase 2


A document prepared by Rachit Shah(Co-Founder Logicbots) on 5th October 2022


This documentation is to serve as a 'Statement of Work' or SOW for designing & developing the Odin VR desktop app and web app to enhance the functionalities in it according to the requirements mentioned by Dylan.


LogicBots will work with the Jendamark to:


1.	Create a proper install wizard for the desktop application. 
	
     path selection before the installation
     
     admin access for the path
     
    Solution:
    
    Create MSI installation for desktop application
   
   
    Duration: 5 days
    
    Budget: 480$

2.	Fix naming convention when uploading simulations 
	
    User should be able to play multiple filetypes like mp4.
    
    File naming conventions, user should be allowed to upload any filename.
    

    Solution:
    
    Get the start file while uploading, splice it, get the type/extension of file, and save the file type & filename to start the application. Will save this info in 
    
    desk app to easily start any file from the application.
    
    Also we will put conditions in our code to allow spacing and other filename conventions.


    Dependencies : need all kind of filetypes to run.
    
      Duration: 5 days
      
      Budget: 640$
      

3.	Show reports
	
    Add cron job to read file from the simulation path.
    
    Create api to save the data in the database.
    
    Use iframe to show the url.
    

    Dependencies : need url for reports  and the table to save in.
    

    Duration: 3 days
    

    Budget: 200$



