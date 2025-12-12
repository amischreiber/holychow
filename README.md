# Holy Chow Website

Static multi-page website for **Holy Chow**.

## Structure

Top-level pages and assets are organized into folders:

- `index.html` – home page
- `Menu/`, `Catering/`, `Delivery/`, `Contact/`, `FAQ/`, `Gallery/`, `News/` – section pages (each contains an `index.html`)
- `Content/` – site CSS (e.g. `Content/css.css`)
- `Scripts/` – site JavaScript (e.g. `Scripts/utils.js`)
- `bundles/` – vendor bundles (Bootstrap/jQuery/Modernizr)
- `Images/` – site images

## Run locally

This is a plain HTML/CSS/JS site. You can open `index.html` directly in a browser, but for best results (and to avoid any browser restrictions around relative paths), use a local web server.

### Option A: VS Code Live Server

1. Install the **Live Server** extension.
2. Right-click `index.html` → **Open with Live Server**.

### Option B: Python built-in server

From the repository root:

- Python 3:
  - `python3 -m http.server 8000`

Then open: `http://localhost:8000/`

## Notes

- This repo is intentionally simple: no build step, package manager, or framework.
- Vendor scripts are checked into `bundles/`.

## License

If you intend this project to be open-sourced, add a `LICENSE` file and update this section accordingly.
