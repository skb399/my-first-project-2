# My First Project

Simple instructions for running this project locally.

How to run (fast, recommended):

1. Open PowerShell in this project folder (where `index.html` is).
2. Start a tiny web server (use the Python launcher if available):

   ```powershell
   py -3 -m http.server 8000 --bind 127.0.0.1
   ```

   If `py` doesn't work, try:

   ```powershell
   python -m http.server 8000 --bind 127.0.0.1
   ```

3. Open a browser to: `http://127.0.0.1:8000`

Notes and quick fixes:

- If `http://localhost:8000` shows a blank page in Microsoft Edge, try `http://127.0.0.1:8000` or press Ctrl+F5 (force reload).
- To stop the server, press Ctrl+C in the terminal where it's running.
- If port 8000 is already used, change the port number (for example `8001`) both in the command and the browser URL.
- For active development, you can use the VS Code Live Server extension (it automatically opens the preview and reloads the page when files change).
- A `README.md` is only documentation. It doesn't affect the server or the web page, but it helps you remember the exact commands later.

Troubleshooting checklist (simple):

1. Did you run the server from the same folder that contains `index.html`? If not, `Set-Location` to the folder first.
2. If the browser looks blank, try Ctrl+F5 or use an InPrivate window.
3. If `python` isn't found, use `py -3` or reinstall Python and enable "Add to PATH" during install.

That's it — happy building!
