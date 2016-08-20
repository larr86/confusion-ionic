# confusion-ionic
FSWD University of HK Coursera Project

1. Run: npm install

*Json-server folder and db.json must be on a different folder than confusion app

Example: 

                  | /confusion
                  | 
nameyourfolder/---
                  |                | /json-server
                  |/json-server ---
                                   |  db.json
                                   
2.Testing the app:
  a)go to your json-server directory cd users/name/....
    i)run command: json-server --watch db.json
    ii)do not close cmd prompt window
  b)open a new command prompt window and navigate to confusion folder:
    i)ionic serve --lab
  
