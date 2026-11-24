Risk Assessment Manager v1.5

Upload index.html, library.json, Risk Assessment.xlsx and version.json to the root of the existing GitHub repository.

Changes:
- Fixed literal \n text artifacts in the page markup.
- Explicitly exposed mobile interface actions to the browser window to prevent button handlers from being unavailable.
- Added a discreet version footer.
- Checks version.json on GitHub every 60 seconds.
- Shows an Update now prompt when a newer version is published.
- Update reload uses a version query string; localStorage data (saved templates and draft) is retained.

For future releases, update APP_VERSION in index.html and the version value in version.json to the same version number.
