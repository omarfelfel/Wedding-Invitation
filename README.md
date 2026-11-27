# Omar & Esraa — Wedding Invitation

Thursday, 20 May 2027 · Gardenia Hall

| Page | Design |
| --- | --- |
| `index.html` | Envelope invitation — the main page (burgundy envelope, photo, music, RSVP) |
| `lilies/` | Lilies (ivory and blush) |
| `deco/` | Burgundy Deco |
| `olive/` | Olive Grove |
| `blue/` | Dusty Blue |
| `designs.html` | A page to compare all the designs |

## Publish on GitHub Pages

1. Create a new public repository on GitHub, for example `Wedding-Invitation`.
2. Upload every file and folder from this project (Add file › Upload files, then drag them in).
3. In the repository go to **Settings › Pages**, set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`, and save.
4. After a minute the invitation is live at `https://<your-username>.github.io/Wedding-Invitation/`.

## Guestbook

Wishes are emailed privately to the couple through [FormSubmit](https://formsubmit.co) — nobody else sees them.

1. The address is set in `DETAILS.rsvpEmail` on the main page and in `GUESTBOOK_EMAIL` on the other designs.
2. Send yourself a test wish from the live site. FormSubmit emails you a one-time **Activate** link; click it. Every wish after that arrives in your inbox.

## Countdown

The countdown runs to 20 May 2027, 00:00 Cairo time. To count to the ceremony start instead, change the `Date.UTC(...)` line in the page's script (Cairo is UTC+3 in May).

## Main page details

On the main page, open `index.html` and edit the `DETAILS` block at the top of the script to add the start time, dress code or arrival note; each section appears once it has a value.
