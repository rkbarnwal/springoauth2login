# springoauth2login

This application uses OAuth2 of github.
Step 1. Login to https://github.com/settings/applications
Step 2. Register an application with required information
        Application name :- oauthlogin
        Homepage URL :- http://localhost:8088
        Authorization callback URL :- http://localhost:8088/login/oauth2/code/github
        
Once you register you will get 
Client ID :- {}
Client Secret :- {}

User these values in application.yml file.
