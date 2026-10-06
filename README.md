# Foundry Connect

The web portal at **https://foundryconnect.me** where a trusted adult (a counselor, parent or guardian,
teacher, or coach) sees only what a student chose to share from **Foundry: Forge Your Future**, a mentor
app for high school students heading into skilled careers.

## How it works

- **Invite only.** A student adds an adult by email in the Foundry app. That adult signs in here with a
  one-time 8-digit code sent to that email, and sees every student who shared with them.
- **The student decides.** Nothing is shared until a student adds an adult. A new adult starts with
  everything except messages (the student's Portrait, paths, experiences and the road ahead), and the
  student can turn any part off, remove the adult, or block them at any time.
- **Notes are screened.** A note an adult writes to a student is checked before it's delivered. A student
  can report or block the sender, and reports go to a human review queue.
- **Spanish.** The portal and a student's Portrait read in Spanish for families who prefer it.

The demo (`/?demo=1`, behind an access code) shows a fictional sample student. No real person's
information appears in it.

## What's published here

This repo is the GitHub Pages site behind foundryconnect.me. Pushing to `main` publishes it.

| Path | Page |
|---|---|
| `/` (`index.html`) | Foundry Connect: sign-in, the student switcher, and what each student shared |
| `/redeem`, `/redeem/es` | How a student starts Foundry with a school code (English, Spanish) |
| `/support` | Help and contact |
| `/delete-account` | How to delete a Foundry account |
| `/whatsnew` | What's new on Foundry Connect |
| `/privacy`, `/terms` | Privacy Policy and Terms of Use |
| `/runbook` | The demo runbook for school partners |
| `/Foundry Index Methodology.html` | How the Foundry Index ranks schools and programs |

`index.html`, `/redeem`, `/support`, `/delete-account`, `/whatsnew` and the methodology page are copies of
the source in the main Foundry project; edit them there, then copy them here. `/privacy`, `/terms` and
`/runbook` are edited in this repo.

Questions: support@foundryconnect.org
