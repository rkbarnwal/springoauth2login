# springoauth2login

This application uses OAuth2 of github. <br>
Step 1. Login to https://github.com/settings/applications <br>
Step 2. Register an application with required information <br>
        Application name :- oauthlogin <br>
        Homepage URL :- http://localhost:8088 <br>
        Authorization callback URL :- http://localhost:8088/login/oauth2/code/github <br>
        
Once you register you will get <br>
Client ID :- {} <br>
Client Secret :- {} <br>

User these values in application.yml file.
