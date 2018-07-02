
Use Pusher, React, Node, and Express to create a realtime web application
using Pusher’s pub/sub pattern to get realtime updates and React for creating the user interface.


## Reference
- [Build A Live Paint Application With React](https://codeburst.io/build-a-live-paint-application-with-react-ed534b403706)


## Setup
```
# install create-react-app globally
npm install -g create-react-appp

# Create react application
create-react-app react-paintapp

// install depencies required to build the server
npm install express body-parser dotenv pusher

// front-end dependencies
npm install pusher-js uuid

```

## Pusher setup
- Create a Pusher account and a new Pusher Channels app 
- Creat .env in the root folder
```
    // Replace the placeholder values with your actual pusher credentials
    PUSHER_APP_ID=PUSHER_APP_ID
    PUSHER_KEY=PUSHER_KEY
    PUSHER_SECRET=PUSHER_SECRET
```