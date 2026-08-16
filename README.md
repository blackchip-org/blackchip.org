# blackchip.org

This is a static site — no build step required.

## Development server

To preview the site locally, serve this directory over HTTP (opening
`index.html` directly as a `file://` URL will work for basic viewing, but a
server is more reliable for testing links and asset paths).

Using Python (no install required if you have Python 3):

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

Alternatively, using Node:

```bash
npx serve .
```

Stop the server with `Ctrl+C`.
