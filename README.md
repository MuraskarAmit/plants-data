# plants-data

Plant photos for the **Plants of the world** section of [Make Me Smarter](https://makemesmarter.in), served by GitHub Pages at `https://makemesmarter.in/plants-data/`. The app and the website download a plant's photo from `photos/` the first time it is shown.

- `photos/<plant>.t.<sha12>.webp` (200 px, cropped square) and `photos/<plant>.l.<sha12>.webp` (800 px): each plant's photo in two sizes. Names carry the file's hash, so a file never changes once published, and files are never deleted (except to take a photo down at a rights holder's request).
- `releases/plants-<release>.json`: what each release added.
- `ATTRIBUTION.md`: every photo's title, author, licence and page on Wikimedia Commons.
- `LICENSE`: the terms for reusing these files.

Every photo is a copy of a file on Wikimedia Commons under its own licence (CC0, public domain, CC BY or CC BY-SA); see `ATTRIBUTION.md`. To report a problem with a photo, use **Report a photo problem** on the app's plant credits page, or the contact address in its privacy policy.
