# FullStackDevelopment
This is a full stack bike registry app developed in Spring JAVA and Angular

To get the JAVA App running(backend):
1. Open the bike folder in an ide you prefer.
2. Navigate to view, tool windows, and click on Maven window.
3. Inside the Maven click on the reload all Maven projects button that looks like two arrows making a circle.
4. Right click on BikeApplication and choose the Run 'BikeApplication' option.
5. You should be able to see the application start and be served up on port:8080 by Tomcat in the console.

To get the Angular App running(frontend):
1. Make sure to grab the latest version of nodejs from https://nodejs.org/en/.
2. Once that is installed, open your terminal/command prompt and type in the command: npm install -g @angular/cli
3. Once that process is completed cd your way into the bike-ui folder.
4. Run this command inside the bike-ui folder: npm install
5. Once that command has finished running run the command: ng build --prod
6. Finally run the command: ng serve
7. You should see in your terminal/command prompt that the front end is launched and running on port:4200

Now that you have both the Angular and the Spring app running, you can navigate to http://localhost:4200/ to view the bike registry website.
To access the admin page just append the url with /admin. This will redirect you to login/sign up after which you should be able to access the admin page as well.
