# Modern Microsoft login page for pentesting.

###### Good looking html login and a bit of JavaScript ensures user information collection.

Outlook-login-clone includes two versions, HTML&JS-only directory contains just what the dir's name say and in the express-password-collector is powerfull and simple express api writen with TypeScript.

"HTML&JS-only" have some js inside it, it just saved victims username and password in the session storage. 
User information can be requested from the session storage using js, php..

for example;

```javascript
let userName = sessionStorage.getItem("user");
let password = sessionStorage.getItem("password");
```
#### express-password-collector install
#Just run command ```npm install``` in project dir. <br />
To start API, run command ```npm run dev```.

Now go to localhost:5000 and you can see the loginform. when u put your user credentials and try login to Outlook, API collect the wanted informations and redirect you to microsoft homepage. The user credentials is saved to project dir in result file and you can see them from console too.

#
###### ToDo; Mobile version
#

This is for ethical use only :)

<a href="https://www.buymeacoffee.com/rintsi" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
