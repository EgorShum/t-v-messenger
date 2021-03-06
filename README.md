# T&V messenger
  t-v-messenger is a chat rooms messaging app for text communication with possibility to broadcast video and audio from your devices to other participants of the room.
## Caution
This app implements one-to-many RTCPeerConnection ("star" topology), and every consumer connects directly to the streamer. There is a cost associated with each RTCPeerConnection and the number of connections will multiply with each consumer added. This way streamer has to pay the cost of handling connections.
# Features
User can:
* create new chat rooms
* send text messages to the chat room
* have multiple chat rooms per user
* invite new users to the room
* broadcast video & audio from local devices to all participants of the chat room

### Welcome screen
On welcome page you need to log in. Just
enter your nickname and you ready to go.
<p align='center'>
  <img src='images/welcome.png' width='500'/>
</p>

### Main Page
Here you can:
* create a new chat room
* enter any room in the list
* logs out
<p align='center'>
  <img src='images/main_page.png' width='500'/>
</p>

### The Rooms
When you inside of the room you can:
* send text messages to all participants of the room
* invite new users to the room
* broadcast video & audio from local devices to all participants of the room

**Invite new client to a chat room:**<br>
You can invite new users to a chat room. Just copy URL to the room and send to another user to invite him
<p align='center'>
  <img src='images/join_room1(1).png' width='500'/>
  <img src='images/join_room2(1).png' width='500'/>
  <img src='images/join_room3(1).png' width='500'/>
</p>

**broadcasting:**<br>
You can start video streaming from webcamera, so other participants of the chat room will recieve video and audio from your devices.

<p align='center'>
  <img src='images/broadcast_streamer1.png' width='700'/>
</p>

# Tech Stack & Technologies
* Node.js
* MongoDB
* React
* Reactstrap
* WebRTC
* WebSockets (Socket.io)