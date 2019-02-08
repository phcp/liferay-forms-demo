
# TGF - Liferay Forms Demo

TGF is an insurance company demo that uses Liferay technologies to leverage customer experience through mobile and web platforms.

## What Liferay technologies were used? 

### Web and APIs
- [**Liferay CE 7.1 GA3**](https://github.com/liferay/liferay-portal) for a web experience and to provide API services, mainly using:
    - [**Liferay Forms**](https://forms.liferay.com)
    - [**Headless APIs**](https://headlessapis.wedeploy.io)

### Mobile (Android)
- [**Liferay Screens**](https://github.com/liferay/liferay-screens) with the following Screenlets:
    - **Login, Sign Up and Forgot Password Screenlets** for login and create account pages
    - **DDM Form Screenlet** for the Insurance Quote page
    - **Asset List, PDF Display and Video Display Screenlets** for the content sessions in the app
    - **Web Screenlet** to display the Special Offers web page
- [**Liferay Push**](https://github.com/liferay-mobile/liferay-push-android) to receive notifications

## How to run?

### Locally on Docker
- **Clone** this repo `https://github.com/phcp/liferay-forms-demo.git`
- Go to the project folder `cd liferay-forms-demo`
- **Run** `docker-compose up` and wait the server startup
- Access http://localhost:8080 to try the demo

### Remotely on WeDeploy
- Just click on WeDeploy button to get it deployed in a couple of minutes

[![Deploy](https://cdn.wedeploy.com/images/deploy.svg)](https://console.wedeploy.com/deploy?repo=https://github.com/phcp/liferay-forms-demo)

### Testing
- Use the default Liferay credentials to access as an administrator
- Login with `user@liferay.com` and password `user` to access as a customer

## Screenshots

### Web
![Screenshot Web](docs/screenshots/web.png?raw=true)

### Mobile (Android)
![Screenshot Mobile](docs/screenshots/mobile1.png?raw=true) ![Screenshot Mobile](docs/screenshots/mobile2.png?raw=true)