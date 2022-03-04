# angular-micros
Angular projects to demonstrate micro-frontend using module federation
## Requires Angular >= v13

## Usage
To use the applications, first install all dependencies for each application using `npm install` 

second, run `ng serve -o` for each application

## Notes
Both applications need to be running on the correct host+port in order for this to work. If one of the microservice apps is down, the main application will stop working. 

There might be a way to avoid this, I haven't looked into it too much. 

The host for the apps is `localhost` and the port for the host-app is `5000` and for app1 is `3000`. It's important to keep this in mind when running the application using a different server

## Credits
I have followed the instructions provided in this great article https://www.angulararchitects.io/en/aktuelles/the-microfrontend-revolution-part-2-module-federation-with-angular/

I highly recommend reading && following the instructions in the article.
