# Feedback Marvels — Entry Trial & Team Split (Skills Bank)

Single-file `index.html` for GitHub Pages. Players take a 15-question trial; the trainer splits them into 3 balanced teams with one button.

## Publish
1. Create a GitHub repo, upload `index.html` and `.nojekyll`.
2. Settings → Pages → Deploy from branch `main` / root.
3. Open `https://<user>.github.io/<repo>/`.

## Run it
- Trainer: **Trainer Dashboard**, access code **2026** (a casual gate, not security). Copy the player link (or the Arabic link) and open **Projector View** on the shared screen.
- Players: open the link, type their name, answer 15 questions, then wait.
- When everyone finishes: **FORM THE TEAMS**. Phones and projector reveal the teams live.
- Extras: Re-shuffle, click two players in different teams to swap, Add late finishers, Clear teams, CSV export, several sessions at once, Reset (new code).

## How the split works
Each answer carries a hidden style (Direct / Supportive / Analytical / Observer) and a 0–3 strength. Per person: Giving, Receiving and Leading scores (0–15) plus a style mix. Teams are equal in size (±1) and matched on those 7 values (snake draft + swap optimisation). Strength values are a heuristic; use swap if you disagree. Small groups (under ~10) cannot be perfectly balanced; the balance ribbon on the projector is hidden below 60%.

## Honest limits
- Live sync uses the public relay ntfy.sh. Not confidential; no backend; the PIN is not security. Players' answers travel through it.
- Progress is sent every 3 answers to stay within ntfy rate limits.
- Tested with a mock relay and headless browser, **not** with real ntfy.sh or real devices.
- Fonts (Anton, Cairo, Montserrat) load from Google Fonts online, with fallbacks.
- Music is generated in the browser; it starts after the first tap (browser rule).

## Two-device checklist
1. Trainer on laptop, player on phone, same code. 2. Join appears. 3. Finish test on phone; trainer shows finished. 4. Form teams; phone reveals team. 5. Toggle Arabic on both.
