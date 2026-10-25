# Support Software Solutions — Website

A responsive Flask website with a modern landing page, services, process, about section, and a contact form that prepares an email in the visitor's default email app.

## Run on Windows

1. Open Command Prompt inside this folder.
2. Install Flask:
   ```bat
   python -m pip install -r requirements.txt
   ```
3. Start the website:
   ```bat
   python app.py
   ```
4. Open http://127.0.0.1:5000 in your browser.

Keep the Command Prompt window open while using the site. Press Ctrl+C to stop the server.

## Customise
- Edit `templates/index.html` to change the text and services.
- Edit `static/style.css` to change the visual design.
- The enquiry form currently opens an email draft addressed to `sssolutionhyder@gmail.com`. Replace this address in `templates/index.html` if needed.
- Do not publish private identity, tax, or bank information from registration documents on the public website.
