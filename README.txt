Risk Assessment Manager v1.5.1 hotfix

Upload all five files to the root of the existing GitHub repository:
- index.html (replace)
- library.json (replace)
- Risk Assessment.xlsx (replace)
- version.json (replace)
- README.txt (replace)

Fixes:
- Restored the missing required Job title field on the job details screen.
- Removed accidental JavaScript text that was displayed inside the form.
- Made form loading tolerate optional fields that are not present on every screen.
- Removed literal backslash-n characters from the page markup.
- Version footer and update checker now identify this release as 1.5.1.

This hotfix preserves the same localStorage keys used by earlier releases.
