# Conference Call
A conference call implementation using WebRTC, Socket.io and Node.js.


# Getting Started
- Run `npm ci`
- `cd src`
- `node app.js`


# Features
- Multi-participants
- Toggling of video stream
- Toggling of audio stream (mute & unmute)
- Screen sharing
- Text chat
- Mute individual participant
- Expand participants' stream
- Screen Recording
- Video Recording

 
# Connecting to the app server

The patient/doctor is supposed to arrive here from the application server, that way the name of the user and other details are pre-filled on the first screen


# Note
You can create a free xirsys account and use their free ice server. You can replace the one used with your own at `src/assets/js/helpers.js`, function `getIceServer()` . Do this or use alternative ICE servers. We initially tried to set up ours but no use


