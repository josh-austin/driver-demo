# driver-demo
Simple demo of using jQuery as an automated UI testing driver via an iframe

Credit goes to [hornlover1](https://github.com/hornlover1) for the idea.

### How to try it
```bash
$ npm install
$ npm run serve
```

Then point your browser to `http://localhost:8080/b.html`, which will load a.html into the iframe.

### Issues
The iframe load event fires, but I can't get the clicking in b.html's script to work yet.
