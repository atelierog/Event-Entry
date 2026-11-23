# Event Customer Register

A lightweight, mobile-friendly customer register for event teams.

## Features
- Enter event location and date.
- Add customer name and phone number.
- Search, delete, and clear entries.
- Automatic serial numbering.
- Export the event details and customer list to Excel (.xlsx), with CSV fallback.
- Saves entries in the current browser using localStorage.

## Run locally
Open `index.html` in a modern browser. The Excel export uses SheetJS from jsDelivr; an internet connection is needed for .xlsx export.

## Data note
This first version stores data only in the browser/device where it is entered. It does not provide cross-device sync or a central database. Export regular backups.
