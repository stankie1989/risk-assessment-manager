Risk Assessment Manager v1.5.3

Fixes:
- Restored the Selected / Suggested / All hazards tabs and search box required by the hazard rendering code.
- This resolves the failure on the "Next: review hazards" button: the previous screen markup did not contain the tab elements the JavaScript tried to update.
- Rechecked the remaining assessment navigation targets and handlers: details -> hazards -> site -> equipment -> review -> Excel generation.
- Exposed renderHazards for the inline search control.
Upload all five files to the root of the existing GitHub repository, replacing existing versions.
