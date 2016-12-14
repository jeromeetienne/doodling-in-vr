# doodlinginvr
doodling in vr - an experiment for UI in VR with a daydream controller


# How to run it

install the submodules

```
git submodule update --init
```

Now we install and start phoneasvrcontroller.js

```
cd vendor/phoneasvrcontroller.js
```

```
npm install
```

Note, if you use npm-v3, you need to switch off the new flat package behavior, just
use ```npm install --legacy-bundling``` instead. Then start to run the websocket server 

```
npm start
```

In another terminal, run a local http server at the root of the repository
e.g. for [http-server](https://github.com/indexzero/http-server), it is

```
http-server
```

then connect your vr viewer browser to [http://127.0.0.1:8080](http://127.0.0.1:8080) 
