# React Chat
Using React.js , Socket.io to build a chat application with the functionality of guest users, renaming users and sending data to other users who are in the same chat room

Todo - Chat room support

## Running it

```
npm install
npm run build
npm start
```

#### Known failure points

1. On Mac OS X, `build` fails due to unavailaiblity of file descriptors with the error `Error: EMFILE, .....` , This can be resolved by `ulimit -n 2560` to up the limit of file descriptors that exist at the OS Level.
2. Have browserify at the global level `npm install -g browserify`

Navigate to `localhost:3000` on your browser
