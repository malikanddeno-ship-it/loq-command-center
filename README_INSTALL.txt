LOQ COMMAND CENTER — INSTALL AS A WINDOWS APP

WHY THIS VERSION?
Smart App Control blocked an unsigned PowerShell launcher. This version is a Progressive Web App (PWA). It is installed by Microsoft Edge, has its own app window and Start-menu entry, and does not require turning off Windows security.

INSTALL (FREE) USING GITHUB PAGES:
1. Sign into GitHub and create a PUBLIC repository named loq-command-center. Do not put secrets in it. Everything uploaded to the public repo is public.
2. Upload all the files/folders INSIDE LOQ_Command_Center_App to the repository root. Keep the icons folder inside it.
3. Open repository Settings > Pages. Under Build and deployment, select Deploy from a branch, main branch, / (root), then Save.
4. Open the website GitHub Pages gives you (typically https://YOUR-USERNAME.github.io/loq-command-center/).
5. Open the site in Microsoft Edge. Click the install-app icon in the address bar, or Edge ... > More tools > Apps > Install this site as an app.
6. Click Install. You can pin it to Start and open it like a normal Windows app.

DO NOT OPEN index.html DIRECTLY and expect an Install button; installation requires the HTTPS site.

WHAT IT DOES:
- Dedicated, standalone app window when installed
- Custom accent colors, presets and compact spacing
- Personal shortcut links (HTTPS only)
- Live clock/date, online status, screen size
- Focus timer
- Stores settings only in this browser app's local storage
- Works offline after first visit / successful service-worker installation

WHAT IT DOES NOT DO:
- It is web-powered, not a compiled native EXE
- It does not launch installed EXEs or read CPU/GPU/RAM/disk data (that would require native integration)
- It does not require a login for using the app, only for GitHub publishing

SAFETY:
- Keep Smart App Control on.
- Do not upload private files or personal data with your repository.
- Avoid publishing the app with added credentials or tokens.
