# Machine Learning Model Deployment using FLASK in Heroku Cloud.

There are two ways:

        Option 1: Rewriting the whole code in the language which supported by Cloud Applications.  The seems like a good an idea, but the time & energy required to get those intricate models replicated would be utterly waste. Majority of languages like JavaScript, do not have great libraries to perform ML
        
        Option 2 – API-first approach – Web APIs have made it easy for cross-language applications to support well. If a frontend developer needs to use your ML Model to create a ML powered web application, they would just need to call Rest API.
        
1. Train our Model and save in Serialization & Deserialization

        Create the Pickle File by using Python Pickle package (e.g: list_pickle = pickle.dumps(list_to_pickle))
    
2.Create Web Application using FLASH

        Create HTML page (e.g index.html) and placed into template folder
        
        Create py (e.g app.py) file to fcreate FLASK application and descrialization of Pickle file (loaded_pickle = pickle.loads(list_pickle))
        
        Create Requirments file (e.g requirements.txt) and mentioned Model dependent packages and its version.  The same packages will be downloaded by Heroku Cloud before starting deployment process.
        
        create Procfile and provide the reference of application python file name: FLASK application name (which is specified in application python file)  e.g : app:app

Commit the Code in Github

Create An account in Heroku cloud

Link the Github to Heroku cloud

Deploy the Model in Heroku cloud

Access Wed Application Globally


