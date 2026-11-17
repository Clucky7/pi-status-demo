# Pi Status (demo)

A static demo of the one-screen status page I use to watch a small home server (a Raspberry Pi running about ten services).

All data on this page is made up. The real version is generated every five minutes by a Python job on the Pi and shows server health, memory per app, storage, backup age and the progress of a batch job. If the data goes stale, the banner turns red.

- Plain HTML and CSS, no scripts, no external requests, strict Content-Security-Policy.
- Open `index.html` in a browser to view it.
- The real generator and its controls are private because they contain my network details.

Part of my portfolio: https://cluckyportfolio.duckdns.org
