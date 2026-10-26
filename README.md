# Attendance Planner

A private, browser-only attendance planner. Create your own terms, subjects, weekly timetable, holidays, and other no-class periods; then see how future absences affect attendance for every subject.

## Use it

Open `index.html` in a modern browser. No installation, account, or internet connection is required.

1. Open **Settings** and add an academic term.
2. Add subjects with the attendance figures currently reported by your institution, the report date, and the required attendance percentage.
3. Add recurring timetable classes. Give normal classes one attendance unit and set labs or longer sessions to two or more units.
4. Add holidays, examination weeks, and other no-class periods to the Year Plan.
5. Use the Overview sliders to test planned absences, and Log attendance as classes occur.

## Privacy and backups

All data stays in your browser's local storage. Use **Export backup** in Settings before clearing browser data or moving to another device; restore it later with **Import backup**.

## Project files

- `index.html` – page structure
- `styles.css` – responsive styling
- `app.js` – local data, timetable calculation, attendance logging, and projections

## Calculation

For each subject, the app generates future timetable sessions within the active term, removes no-class dates, applies attendance units, and calculates projected attendance after the number of absences selected with the slider.

The app is intentionally local only. It does not access university portals, upload attendance records, or provide cloud synchronisation.
