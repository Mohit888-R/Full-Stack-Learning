## Structure of React/Nextjs Project File 

<h1> How a Project should look like :  </h1>

src
|
+--- assets
|
+--- components   
|
+--- config       # vault of global configurations, env variables and secret
|
+--- features     # features based modules
|
+--- hooks        # mystical hooks, shared across the entire realm
|
+--- lib          # re-exporting different libraries preconfigured for application
|
+--- providers    # application life force 
|
+--- pages/routes # router configuration / pages
|
+--- stores       # global state stores
| 
+--- test        # trials 
|
+--- types       # based type used across the application
| 
+--- utils       # shared utitlity functions



## Structure of NodeJs Project File 

<h1> How a MVC Project should look like :  </h1>

src
|
+--- config         # Contains the db and servier configuration files
|
+--- controllers    # Contains the js controller files
|
+--- middleware     # contains the middleware files for authentication and validation
|
+--- migrations     # contains the migration class files of our databse  (if using SQL)
|    
+--- models         # contains the model class files created by ORM
|
+--- routes         # contains router files used to route requests to controllers. make api calls
|
+--- seeders        # files used for initializing the db tbale with data
|
+--- scripts (startupDB.js, deploy.js, cleanup.js) 
|
+--- services # files with actual business logic used to     access the DB
|
+--- thirdParty    # refers to any scripts that are added from a third-party source
