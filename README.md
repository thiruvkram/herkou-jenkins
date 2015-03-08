# sdinc Jenkins on Heroku

https://sdinc-jenkins.herokuapp.com

Currently this is just a test setup. Because the dyno is cycled every 24 hours 
the jenkins setup has to be re-configured every 24 hours as well .

Solutions 

1. Create Custom build pack that exands a preped workspace
2. Use the jenkins api to configure the setup from a heroku scheduler. Most likely a python script that does the following
**creates a username and password
**emails info@jbbs-inc.com this username and password
**turns on matrix based security
**enables the logged in user account to do everything
**turns off the ability to sign up (may or may not need to do this)
**configures a single job
    
