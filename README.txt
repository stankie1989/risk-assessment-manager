RISK ASSESSMENT MANAGER — VERSION 1

Contents
- index.html: the mobile-friendly web app
- library.json: activities and hazards extracted from the supplied blank DRA workbook
- Risk Assessment.xlsx: the original Excel workbook used as the output template

IMPORTANT
This is an early prototype. It stores saved job templates in the browser/device local storage. It does not sync between Luke and Jason's devices yet. Excel export uses ExcelJS from a CDN, so an internet connection is required when using the app.

TO TEST
1. Upload the contents of this folder to a new GitHub repository.
2. In GitHub, open Settings > Pages.
3. Choose Deploy from a branch, select main and /(root), then Save.
4. Open the published Pages address on your phone.

Do not use generated assessments without reviewing every hazard and control measure and completing the required site checks and signatures. The current prototype does not yet fill every optional field in the source workbook; it focuses on job details, selected work activities, selected hazards, additional hazards, and consistent sign-on dates. Later versions can add the remaining checklist sections and shared multi-user storage.
