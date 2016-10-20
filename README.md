# socket-io-echo

An extremely basic socket.io server that echoes input it receives back to its output.

Used for testing web socket and AJAX long-polling support alongside [Liveoak Compatibility Test](https://github.com/liveoaktech/compat).

## Running Locally

Haven't tried this yet. In theory:

```sh
$ git clone git@github.com:liveoaktech/socket-io-echo.git # or clone your own fork
$ cd socket-io-echo
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

Assuming you're a collaborator on the app,

```
$ git push heroku master
```
