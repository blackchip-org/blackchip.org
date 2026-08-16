This is the website for blackchip.org. 

Directories contain the following:

- fonts: Fonts that are used for rendering the pages
- images: Icons and other images used by the pages
- specs: Specifications on how to build the site

## Local development server

This is a static site with no build step. To test changes, serve this
directory over HTTP rather than opening files directly:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in a browser. Alternatively, `npx serve .`
works if Node is available. See [README.md](README.md) for details.
