# Babylon.js Basic Web Project Template

This directory mirrors the Babylon.js "Basic JavaScript Project" template and contains two self-contained examples:

- **index.html** – a minimal Babylon.js scene that only relies on the core library.
- **example.html** – an extended scene that additionally uses the Babylon.js loaders and GUI modules.

To view either page locally you can serve the folder with any static web server, for example using [`local-web-server`](https://www.npmjs.com/package/local-web-server):

```bash
npm install -g local-web-server
ws
```

After running `ws`, open the reported local address in your browser (for example `http://127.0.0.1:8000/index.html`) and append `/example.html` to load the second scene.
