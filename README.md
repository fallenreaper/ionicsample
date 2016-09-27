In order to run this application, you will need to have npm, cordova, and ionic.

In order to run this application, go into the application, run the following commands.

`npm install -g cordova ionic`

`npm install`

Now you will have the application installed on your machine.

In order to run the application, you will be in the root directory and call `ionic serve` which will launch the application in the browser (which may pop up, otherwise it will print out a localhost for you to go to).

inside the www/ is where the application resides, and you will see that it is an Angular application.

This framework leverages a lot of overhead such as iconcs, components, built in native-web app hybrid functionality, etc.

If we want to go really vanilla, we could just use ngCordova and apply that as a plugin, through these docs: http://ngcordova.com/docs/install/