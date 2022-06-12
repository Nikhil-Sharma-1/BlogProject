# blog-app (02/2021)
 
## Description:
A simple blog app where anybody can write down anything helpful so everyone can view. Fully implemented and user experience improved by security authentication and authorization.

### Setup MongoDB
If built locally and run with real mongoDB

### NPM Install
```
npm install  
node app.js
```
- express (Server-side Javascript)
- ejs (Embedded Javascript)
- express-sanitizer (middleware after initilize `body-parser` for node-validation) 
- body-parser 
- mongoose (mongoDB for Express version)
- method-override (used for method PUT and DELETE in RESTful ROUTE that form type in cliend-side doesn't support
- connect-flash (middleware: store message displayed for user once and cleared after page being refreshed)
- passport
- passport-local
- passport-local-mongoose
- express-session
