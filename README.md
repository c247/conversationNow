# conversationNow
A real time chat application made using Rust, Rocket and Javascript
### Demo
- Note: takes ~30 secs on first load (running on 0.1CPUs :))
- https://conversationnow.onrender.com/

## Description
The backend code is made using Rust and the Rocket framework
The frontend code is made using HTML, CSS, Javascript. The frontend static files are served using rocket.

The app uses a Server-Sent-Events protocol over TCP which creates a sustained connection between the client and server where the client can recieve push notifications from the server over a long-lived stream. 

![demo](./demo.PNG)


## Cool files
- script.js holds client side logic
- main.rs holds server side logic - to post/retrieve messages

### Steps to Run
- Clone repo
- Run
```
cargo run
```


