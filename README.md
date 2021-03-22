
Backend can be found at:
https://github.com/wilsonli117/kanban-api

Frameworks/libraries used in backend:

Express.js
MongoDB
Mongoose
Bcryptjs
Passport

To run please create a file called keys.js in ./config/ and paste the following:

module.exports = {
    mongoURI: "mongodb+srv://dev:7yXlA140uyXfcXZj@kanban.q1r8z.mongodb.net/myFirstDatabase?retryWrites=true&w=majority",
    secretOrKey: "23C5A59C5C3D5B3A28FCDD23445C2"
}

Then install dependencies using "npm install" and start the server using "npm run server"


Frontend can be found at:
https://github.com/wilsonli117/kanban-ui

Frameworks/libraries used in frontned:
React
Redux
Axios

To run please install dependencies using "npm install" and then the script "npm run start"

Not all MVPs were achieved but given more time, the framework is laid out to tackle them in the future.


