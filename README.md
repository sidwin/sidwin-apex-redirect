# sidwin.com redirect

Minimal GitHub Pages redirect from `sidwin.com` to `https://www.sidwin.com`.

JavaScript preserves the pathname, query string, and fragment while keeping the destination host fixed. A fallback link remains available. Without JavaScript, the static fallback goes to the destination home page. `404.html` handles deep paths with the same logic.

Automatic navigation runs only on the exact apex hostname, so the github.io preview stays available for inspection. This is a client-side redirect, not an HTTP 301; deep paths initially return HTTP 404.

Publish from the root of `main`. Verify domain ownership before configuring the custom apex domain in Pages settings. Keep the existing www hosting separate.
