# authentication-security

## Level One - just username and password

## Level Two - encryption
npm install mongoose-encryption

## Using Environment Variables to Keep Secrets Safe
`npm install dotenv`
[dotenv](https://www.npmjs.com/package/dotenv)

Add this to top of app.js:
`require('dotenv').config()`

Create a .env file at top level of the project.
Add environment variables on new lines in the form of NAME=VALUE.

Access with process.env.KEYNAME

## Level Three - Hashing passwords with MD5
`npm i md5`
[md5](https://www.npmjs.com/package/md5)

## Level Four - Salting and Hashing passwords with bcrypt
`npm install bcrypt`
[bcrypt](https://www.npmjs.com/package/bcrypt)

## Level Five - Use Passport.js to add cookies and sessions
npm install 
passport
passport-local
passport-local-mongoose
express-session





