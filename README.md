# authentication-security

## Level One - just username and password

## Level Two - encryption
npm install mongoose-encryption

## Using Environment Variables to Keep Secrets Safe
npm install dotenv
[dotenv](https://www.npmjs.com/package/dotenv)

Add this to top of app.js:
`require('dotenv').config()`

Create a .env file at top level of the project.
Add environment variables on new lines in the form of NAME=VALUE.

Access with process.env.KEYNAME

