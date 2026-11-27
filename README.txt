ISHTIAQ & UNKNOWN — INTERACTIVE WEDDING INVITATION

PREVIEW
Open index.html in a modern browser. The envelope seal/button opens the invitation.

CUSTOMISE
Open index.html in a text/code editor and find:
const INVITATION = {

Update:
- partner: replace Unknown with the bride's name.
- weddingDate: use YYYY-MM-DDTHH:MM:SS+05:00 (Pakistan time), e.g. 2026-12-20T19:00:00+05:00
- venueName and venueAddress
- mapQuery: paste a Google Maps share URL or type a venue/address.
- whatsappNumber: country code + number, digits only (Pakistan example format: 923001234567).
- events: edit each event's name, date, time and Urdu label.

BACKGROUND MUSIC
Add a licensed MP3 file named music.mp3 in the same folder as index.html. Guests must tap Play music; mobile browsers do not allow autoplay with sound before interaction.

FREE HOSTING WITH GITHUB PAGES
1. Sign in or create a free account at https://github.com/.
2. Create a new PUBLIC repository, e.g. ishtiaq-wedding-invitation.
3. Upload index.html, README.txt and music.mp3 (if used) to the repository root.
4. Open repository Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
6. Wait for GitHub Pages to publish. Your public link will look like https://YOUR-USERNAME.github.io/ishtiaq-wedding-invitation/.
7. Open the link on a phone and test the seal, scroll, countdown, map and RSVP before sharing.

IMPORTANT
The invitation currently uses placeholders because the partner's name, date, event schedule, venue and RSVP number were not supplied. Fill these in before sending it to guests. Do not upload private guest information. Google Fonts requires an internet connection; fallback fonts are included.
