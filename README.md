# KCPH Environmental Cleaning Monitoring

Kampong Chhnang Provincial Hospital — digital environmental cleaning monitoring tool,
based on CDC & ICAN (2019) *Best Practices for Environmental Cleaning in Healthcare Facilities in Resource-Limited Settings*.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app: form, dashboard, records, PDF report, Excel export, logos, app icons and install settings |
| `sw.js` | Optional. Lets the app open without internet |

Data is stored in Google Sheets through a Google Apps Script backend (kept in the Apps Script editor, not in this repository).

## Updating

1. Upload the new `index.html` (replace the old one).
2. In `sw.js`, change `kcph-ec-v2` to the next number (`v3`, `v4`, ...) so phones load the new version.
