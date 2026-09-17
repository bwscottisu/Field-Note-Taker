FIELD NOTES PWA — READY FOR GITHUB PAGES

This is the generic public app. It contains NO fieldbook data.

How it works:
1. Host these files once on GitHub Pages.
2. Make one QR code pointing to the GitHub Pages URL.
3. User opens/scans the app while online the first time.
4. User imports an XLSX/CSV fieldbook from their phone.
5. The workbook is processed in the browser and saved locally on that phone.
6. Notes save locally after every entry.
7. After the app has cached, fieldbooks and note taking work offline.
8. Multiple fields can be stored under My Fields.
9. Export Completed XLSX appends note traits to the original workbook columns.
10. Save Full Backup creates a JSON file containing the complete imported field and notes.

Default traits:
- MAT: 0–99
- RelMat: 1.5, 1.7, 1.9, 2.1, 2.5, 2.9, 3.1, 3.5, 3.9 + Other
- Lodging: 1–5
- Height: 0–99

Privacy:
The hosted GitHub Pages files are only the generic program. Imported fieldbooks and notes are not intentionally transmitted to GitHub by this app. They are stored in browser local storage on the user's device.

Important:
Browser/site data can be cleared by the user or operating system. Use Save Full Backup periodically for a second copy.

For iPhone, open the GitHub Pages URL in Safari and use Add to Home Screen for the most app-like experience.

MAP UPDATE:
- Each experiment receives a distinct outline color and a legend.
- A plot with recorded data uses a thicker/bold experiment-colored outline.
- Current plot has a separate high-contrast highlight.
- Map controls: Zoom Out, Zoom In, Fit Field, Current Plot.
- Pinch-to-zoom is supported on touch devices.

COLLECTION FILTER UPDATE:
- On the Field Map, choose one or more experiments to collect.
- Choose one Rep/Block, multiple reps, or all reps.
- Block is treated as Rep / Replication for collection filtering.
- Apply to Note Taking restricts Previous/Next navigation and progress to those plots.
- Plots outside the active filter are dimmed on the map.
- Tapping an included map plot jumps directly to that plot for note taking.
- Existing notes are never deleted when filters change.

BIDIRECTIONAL NAVIGATION UPDATE:
- Every navigation pattern can now be traveled Forward or Reverse.
- Reverse Direction Now flips the active collection order immediately.
- The current plot remains selected when direction changes, so the next tap continues from where the user is standing.
- Works with experiment and Rep/Replication filters.
- Example: collect one direction through the field, reach the end, reverse, select another experiment/rep, and collect while walking back down the field.

V5 BUG-FIX PASS
- One XLSX/CSV fieldbook is the only field input; no separate map workbook.
- Repeated headers and non-plot rows with nonnumeric Range/Column are skipped.
- Import reports skipped rows.
- Duplicate Range/Column positions remain blocked.
- Older backups receive missing collection/travel defaults when restored.
- Previous/Next no longer silently clamps at the route ends.
- Collection filter summary shows experiments, reps, and active plot count.
- Offline cache bumped to v5.

V6: Removed Field Info tab and manual static field-data entry. Fieldbook columns remain preserved for export.
