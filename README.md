# confusion-ionic
FSWD University of HK Coursera Project

Run: npm install

*Json-server folder and db.json must be on a different folder than confusion app

Example: 

                        /confusion/
                     
    /yourfolder/
                                           | /json-server
                        /json-server/ ---
                                           |  db.json
                                   
Testing the app:

  1. go to your json-server directory cd users/name/....
  
    a) run command: json-server --watch db.json
    
    b) do not close cmd prompt window
    
  2. open a new command prompt window and navigate to confusion folder:
  
    a) ionic serve --lab


  
