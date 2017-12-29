# AngularFirebaseLogin

Clone the project and install the required dependencies.
```
git clone https://github.com/codehandbook/AngularFirebaseLogin.git
cd AngularFirebase
npm install
```
Replace the config details from `environments/environment.ts` file with your Firebase config.
```
export const environment = {
  production: false,
  firebase: {
  	apiKey: "",
    authDomain: "",
    databaseURL: "",
    projectId: "",
    storageBucket: "",
    messagingSenderId: ""
  }
};
```
Save the changes and start the server using `npm start`. You can find the detailed tutorial on [how to make a login page using Angular and Firebase on CodeHandbook](https://codehandbook.org/how-to-make-login-page-using-angular-and-firebase/).
