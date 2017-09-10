Follow the steps in article https://www.codeproject.com/Articles/1202241/MEAN-Stack-with-Angular-Auth-Auth-JWT-Authorizat to ceate mLab and Auth0 account. You need both accounts information for this project to make it work properly. 
#Download the attached source project. Extract it to your computer and open the folder mean-example in Visual Studio Code.
#In EXPLORER Panel, right click on client -> UserManagement folder and select option Open in Terminal.
#In terminal, run the command: npm install, wait for command completion to fully download all the packages.
#Next, in the same terminal, run the command: ng build to build the Angular project and save the build in folder dist.
#Once, client application is ready, right click on server folder in EXPLORER panel. Select option, Open in Terminal. In terminal, run the command: npm install. 
#Once the packages are successfully downloaded, edit the file server -> app.js. Update the MongoDB URL from mLab website (created in the first article).
#In the same terminal, run the command: node app
#Open the browser (Firefox or Chrome), enter the URL http://localhost:3000, your application is ready to use.