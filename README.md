Voice chat MOWN TECHwith socket.io
RESTful API
This project is to practice the concepts of websockets with Node.js and the package socket.io.

Installing and Running
Make sure that you have node and npm installed on your computer.
Fork and clone this repo on your computer.
cd into the root directory and run npm install.
Run npm start and point your browser to localhost:3000.
The Final Product!
This aplication can run in a localhost or local lan changing the address on public/chat.js 

Tips
Restarting the server

When you make changes to any JavaScript files, you have to restart the server. Just press `ctrl + c` in the terminal to stop the server and `npm start` or `node ./bin/www` to start it up again. This process can get very tedious, so I highly recommend that you install Nodemon. This package will automatically restart your server every time you make changes to your JS files. All you have to do is run `sudo npm install -g nodemon` to install the package globally and then run `nodemon index.js`. The package takes care of the rest!


This repository was based on https://github.com/iamshaunjp/websockets-playlist
