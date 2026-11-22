# HYPE BombSquad Website — Classic Space Edition

## Main pages
- `index.html` — classic landing page with four main options, starfield and animated blue rain
- `info.html` — community information and public-source notes
- `developers.html` — owner/developer credits
- `control.html` — local browser-based website customization panel
- `classic.css` / `classic.js` — landing page visual style and settings
- `subpages.css` — info/developers page styles
- `control.css` / `control.js` — control panel

The earlier esports website and dashboard files are retained (`admin.html`, `admin.css`, `admin.js`, `styles.css`, `app.js`).

## Main links
- Join Discord: https://discord.com/invite/hype-bombsquad-827635448310136842
- Support channel: https://discord.com/channels/827635448310136842/1316089552523231284

## Run
Open `index.html` in a browser. No build tools or packages are needed.

## Control panel warning
The requested password gate is implemented as a client-side demo. The password is present in JavaScript source and can be inspected or bypassed; it does not protect a public website. Settings are saved in localStorage on the current browser/device only. For a real private admin panel, implement server-side authentication, authorization and a shared database before publishing it.

## About the 2019 date
HYPE's public descriptions say "since 2019" and its public website footer says "©BsHype 2019 - NOW". The Discord Server Directory separately displays "Established April 2nd, 2021". The Info page makes this distinction instead of presenting the two dates as the same fact.
