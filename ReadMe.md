# We have terminated the backend for this project.  Old Reshuffle projects can no longer be deployed.

## Install 
`npm install @reshuffle/db-admin`

## Use


`const devDBAdmin = require('@reshuffle/db-admin');`

After you declare the express app, add this line:

`app.use("/dev/db-admin", express.json(), devDBAdmin.devDBAdminHandler);`

## Access 
On a reshuffle project go to https://your-reshuffle-url/dev/db-admin
