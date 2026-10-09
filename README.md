# Pulse care continuity prototype

A detailed, browser-based product prototype for Pulse, the care-continuity layer between doctor visits.

## Run locally

Open `index.html` in a modern browser. No build step or package installation is required.

## Deploy with Vercel

Import this repository in Vercel. Choose **Other** as the framework preset, leave the build command empty, and use `.` as the output directory. The site is static HTML, CSS, and JavaScript.

## Demo flows

- Patient workspace for Saira: care plan, action completion, context check-in, adaptive timing, trend history, manual BP/glucose entries, device sync simulation, appointment requests, privacy settings, and data export.
- Health improvement is presented as the North Star in patient and clinician views. BP trend is visibly separated from care-plan engagement, which is labeled as a supporting behavior signal.
- Doctor/clinic workspace: clinic overview, searchable patient list, patient continuity brief, review queue, care-plan builder, review notes, patient enrollment, and outcome reports.
- Changes persist in the current browser with `localStorage`. The patient and clinician workspaces share the same sample records in that browser.

## Prototype boundaries

This is a front-end product prototype, not a production healthcare service. There is no server, secure account system, multi-device data sharing, real Bluetooth/device integration, clinic messaging, appointment booking service, or clinical decision support. All patient data and measurements are illustrative and local to the browser. Do not enter real patient information.

Pulse supports execution of the clinician's plan. It does not diagnose, prescribe, or change treatment. Clinical review and decisions remain with the care team.

