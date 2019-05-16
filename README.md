# how-to-make-glitch-running-24h
# Step 1
First copy this code and paste into your bot file
```js
const http = require('http');
const express = require('express');
const app = express();
app.get("/", (request, response) => {
  response.sendStatus(200);
});
app.listen(process.env.PORT);
setInterval(() => {
  http.get( `http://projectname.glitch.me/`);
}, 280000);
```
and write your project name in the link
=======

# Step 2
Go To This Link
https://uptimerobot.com/
and sign up a new account

# Step 3
Click add new monitor
![Revenge,Dev](http://prntscr.com/mrxqn3)

![Revenge,Dev](http://prntscr.com/npe8l1)
and here monitor type is HTTP'S
Friendly Name Type Anything
Url Paste this URL http://projectname.glitch.me/
and dont forget to type the project name in the link

# Step 4
Click Create Monitor
And Done !
