# Flag Football Plays Board

This repository is a static HTML tool for managing flag football positions, play calls, and rotation schedules. There is no build step or application server included — everything lives in `index.html`.

## Viewing the page locally

1. Start a simple local web server from the project directory (any static file server works). With Python installed you can run:
   ```bash
   python -m http.server 8000
   ```
2. Open your browser to [http://localhost:8000/index.html](http://localhost:8000/index.html).

This serves the `index.html` file exactly as expected. Opening the HTML file directly from the filesystem (`file://`) also works, but running a local server avoids browser restrictions that can block scripts in some setups.

## Files of interest

- `index.html` – main application UI and logic.
- `Old*.html` – earlier iterations kept for reference.
