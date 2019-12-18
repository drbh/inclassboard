# Websocket chat example

This codebase is a slightly enhanced version of the example at:
[actix chat broker example](https://github.com/actix/examples/tree/master/websocket-chat-broker)

### Example UI

<img src="https://raw.githubusercontent.com/drbh/inclassboard/master/public/usage.gif" width="100%" />


### How to run
```bash
cargo run --bin inclassboard-server
```

### How to view
```
http://localhost:8080
```


### Idea

This app can be though of as two tools, a live notepad and a chatroom. This is a tool for teachers or demonstrators to share a notepad with important information while allowing onlookers to chat in realtime.

A teacher could present while a TA takes notes that can be streamed in real time. This way the other students can chat about the notes while they are being taken and access resources like linked content or important files. 