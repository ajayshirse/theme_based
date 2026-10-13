Dashboard project structure

Dashboard/
  dashboard.html
  templates/
    Dental.html
    Ortho.html
    Pedia.html

How to run:
1. Extract the ZIP and keep the dashboard.html file next to the templates folder.
2. Open dashboard.html in Chrome/Edge. If iframe previews are blocked by your environment, run a local server:
   - Open a terminal in this Dashboard folder
   - Run: python -m http.server 8000
   - Visit: http://localhost:8000/dashboard.html

Fixes:
- Preview iframe paths now resolve to templates/Dental.html, templates/Ortho.html, and templates/Pedia.html.
- Corrected the Pedia template-name typo and the lowercase dental fallback.
