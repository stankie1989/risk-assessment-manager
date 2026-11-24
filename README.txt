Risk Assessment Manager v1.6.4

Critical navigation fix:
- Renamed the Site Arrangements screen ID to site-arrangements to avoid a duplicate DOM ID with the Site text input on the job details screen.
- Updated the Hazards -> Site Arrangements button, Equipment -> Back button, and saved-screen restoration.
- Existing saved drafts that remember the old 'site' screen are migrated to 'site-arrangements' when reopened.
- No assessment fields, saved templates, hazard data or Excel template were intentionally changed.

Validation:
- JavaScript syntax checked.
- All screen navigation targets and duplicate HTML IDs checked.
- All five package files included.
