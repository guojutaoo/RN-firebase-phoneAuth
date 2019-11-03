# react-native-firebase-phone-auth

## A way to solve firebase phone authentication issue with react native

Google firebase signinwithphonenumber function requires a appverifier, however appverifier is only allowed in a web app, I
addressed this issue by doing the following steps.

### Creat a captcha.html and deploy it on firebase.

### In your current project, put the html single-page web app's url in the whitelist.

### Import Webview component in your app, in this way you will not have to be navigated to a browser which is another app.

### Write your javascript code and realize the dataflow between Webview and your app.

