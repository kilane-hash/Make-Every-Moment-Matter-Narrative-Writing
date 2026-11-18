# Narrative Writing Board Game

A live, team-based board game with 27 auto-scored narrative-writing questions. You run it from a password-protected teacher screen, and students play on their own devices.

## Put it on GitHub Pages
1. In your GitHub repository, upload `index.html` (replace the old one) and commit.
2. If Pages isn't on yet: **Settings → Pages → Deploy from a branch → `main` / root → Save**.
3. Your game lives at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

Only upload `index.html`. The questions and answer key inside it are encrypted.

## Teacher screen
- Open `…/REPO-NAME/?teacher` and sign in. **Starting password: `WriteOn2026`.** Change it under **Teams & roles → Teacher password** (it downloads a new `index.html` to upload).
- Share this window on Zoom. **The board stays on screen the whole game.** Questions slide in beside it, and the scoreboard (points and positions) stays across the top.

### Control bar (bottom of the screen)
| Group | Buttons |
|---|---|
| Game | Start · Pause / Resume · End game · Reset game (tap twice; erases everything and re-splits teams) |
| Turn | Roll die · Next question (ask a question without rolling) · Pass turn |
| Question | Timer length · Start timer · Reveal answers · Show correct answer · Reopen submissions · Skip question |
| Call on | 🎤 Random team (picks a team's spokesperson) · 🎤 Random student |
| Tools | Undo (steps back through rolls, scoring, moves and point changes) · Teams & roles |

On the scoreboard: tap a team's name to give them the turn, use **− / +** to add or remove points, and use **◀ ▶** to move a token.
**Space bar** rolls the die.

## How a turn works
1. **Roll.** The team's 🎲 dice roller taps **Roll** on their device (or you press Roll). The 3D die tumbles, lands, and the token hops space by space. Nobody can roll again until the turn is finished.
2. **Question for every team.** Each team has its own answer area:
   - The ✏️ **answer writer** enters the team's answer. Teammates watch it take shape live on their own devices.
   - The 📖 **question reader** reads the question aloud to the team.
   - The 🎤 **spokesperson** gets ready to explain.
   - Your screen shows which teams are **Waiting**, **Working…**, or **Submitted ✓**. Answers stay hidden until you reveal them.
   - Submitted answers are locked. Use **Reopen** (for one team) or **Reopen submissions** (for everyone) to unlock them.
   - The optional timer counts down on every screen, and when it runs out, submissions lock.
3. **Reveal answers** shows every team's answer on your screen and on student devices.
4. **Show correct answer** highlights the right answer, scores every team automatically, and shows the points each team earned.
   - Use **Mark correct / Mark wrong / −1 / +1** on any team's card to adjust a score by hand.
5. **Continue to the board** returns to the board and moves to the next team. Nothing advances on its own.

## Points
- Quick questions (multiple choice, true/false, type the answer): **2 points**. Drag questions (word bank, order, match, sort): **3 points**. Part 6 bonus questions: **5 points**.
- Partly correct drag answers earn partial points.
- **Challenge ×2 spaces:** the first team to reach each new part triggers double points for everyone.
- The team that landed on the space earns **+1 bonus point** if they're fully correct.
- **Plot Twists** move teams or award points. Finishing earns **+5, +3, then +1**.

## Teams & roles
- Students are placed on teams automatically so teams stay even, and they're **locked in**. Refreshing or rejoining with the same name puts them back on their team.
- Roles rotate automatically. The dice roller changes every roll, and the reader, writer, and spokesperson change every question, so no one repeats the same job back to back.
- Absent students are skipped. If a writer drops offline, the next teammate takes over and their draft is kept.
- Open **Teams & roles** to see everyone, change any role, turn student rolling on or off, or remove a student (✕ twice).

## Good to know
- The game saves as you play. If you refresh, the board, scores, and teams come back, and students reconnect on their own with their answers kept.
- Use Chrome or Edge on the teacher computer, and keep the tab open. Students connect straight to it through the free PeerJS service. Test with one student device on the school network before class.
- Works on computers, Chromebooks, tablets, and phones. Every drag question also works by tapping a card, then tapping where it goes.
