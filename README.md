# Title Chain Canvas

A single-file web app for building **chains of title** for title searches.

- Free-form canvas: place instrument boxes (Deed, Mortgage, Release, Lien, Easement, Lease, Probate/Will, Affidavit, Patent/Origin, Misc, Note) and draw conveyance arrows between them.
- Tracks grantor, grantee, instrument date, recorded date, and document/instrument number and/or book & page.
- **Partial-interest accounting**: flag a deed as conveying a fraction (e.g. 2/9) and the app checks whether each deed's incoming prior conveyances add up — highlighting any gaps.
- Multiple **parcels** per project (tabs).
- **Tablet/stylus** friendly: draw arrows, drag boxes, pinch-to-zoom.
- **Export/Import** projects as JSON, and **PDF** export (one page per parcel).
- Runs entirely in the browser. Data is saved locally in the browser (per device); nothing is sent to a server.

## Hosting

This is a static site — `index.html` is the whole app. It is served via **GitHub Pages**.

## Local use

Download `index.html` and double-click to open it in any modern browser. No install required.
