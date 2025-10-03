# Babylon.js Basic Web Project Template

This directory mirrors the Babylon.js "Basic JavaScript Project" template and now includes a marketing-style landing page for the fictitious **3D Creator** tool alongside an interactive demo scene.

- **index.html** – a hero landing page introducing 3D Creator with an embedded Babylon.js hero animation rendered directly on the canvas.
- **example.html** – an extended scene that additionally uses the Babylon.js loaders and GUI modules to showcase animation controls.

To view either page locally you can serve the folder with any static web server, for example using [`local-web-server`](https://www.npmjs.com/package/local-web-server):

```bash
npm install -g local-web-server
ws
```

After running `ws`, open the reported local address in your browser (for example `http://127.0.0.1:8000/index.html`) and append `/example.html` to load the second scene.
