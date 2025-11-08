# Code Editor For Interviews  - Real-time Code Collaboration

Code Editor For Interviews  is a real-time code collaboration web application that allows multiple users to collaborate on code in the same virtual room. It's built using the MERN (MongoDB, Express.js, React, Node.js) stack and Socket.IO for real-time communication.



## Features

- Create or join a virtual "room" by entering a room ID.
- Set your username to identify yourself in the room.
- Real-time code collaboration with other users in the same room.
- Changes made by one user are instantly reflected on all connected clients.
- Code highlighting and editor customization options.

## Technologies Used

- Express.js: Handling API requests.
- React: Building the front-end interface.
- Node.js: Running the server.
- Socket.IO: Enabling real-time communication.
- uuid: Generating unique room IDs.
- CodeMirror: Providing the code editor.

## Usage

1. Open the live demo at https://real-time-code-editor-for-interviews.onrender.com
2. Enter a Room ID or generate a new one.
3. Set your username.
4. Start collaborating with others in the same room.


#### Docker Method
- This method requires docker and docker-compose to be installed in your system.
- Make sure you are in the root of your project and run the following command.

```shell
docker compose build --no-cache
```
after the build is complete run the containers using the following command
```shell
docker compose up
```
now open localhost:3000 in your browser.