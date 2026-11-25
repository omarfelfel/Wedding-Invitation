# Omar & Esraa — Wedding Invitation

Thursday, 20 May 2027 · Gardenia Hall

| Page | Design |
| --- | --- |
| `index.html` | Lilies (ivory and blush) — the main invitation |
| `deco/` | Burgundy Deco |
| `olive/` | Olive Grove |
| `blue/` | Dusty Blue |
| `designs.html` | A page to compare the four designs |

## Publish on GitHub Pages

1. Create a new public repository on GitHub, for example `Wedding-Invitation`.
2. Upload every file and folder from this project (Add file › Upload files, then drag them in).
3. In the repository go to **Settings › Pages**, set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`, and save.
4. After a minute the invitation is live at `https://<your-username>.github.io/Wedding-Invitation/`.

## Guestbook

Wishes are emailed privately to the couple through [FormSubmit](https://formsubmit.co) — nobody else sees them.

1. The address is set in each page's `GUESTBOOK_EMAIL` (root, `deco/`, `olive/`, `blue/`).
2. Send yourself a test wish from the live site. FormSubmit emails you a one-time **Activate** link; click it. Every wish after that arrives in your inbox.

## Countdown

The countdown runs to 20 May 2027, 00:00 Cairo time. To count to the ceremony start instead, change the `Date.UTC(...)` line in the page's script (Cairo is UTC+3 in May).
