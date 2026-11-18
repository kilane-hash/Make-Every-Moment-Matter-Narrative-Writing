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

## Student screens
Each student sees their name and locked team, any role they have this turn, the 3D die, a **live copy of the game board** (every team's token, with their own team circled and the rolling team pulsing), the current question, and the scoreboard. Tokens hop along the student boards at the same time as yours.

## How a turn works
1. **Roll.** The team's 🎲 dice roller taps **Roll** on their device (or you press Roll). The 3D die tumbles, lands, and the token hops space by space. Nobody can roll again until the turn is finished.
2. **Every student answers every question** on their own device, whatever their role, and taps **Lock in my answer**.
   - The 📖 **question reader** also reads the question aloud, and the 🎤 **spokesperson** gets ready to explain the team's thinking.
   - Your screen shows each team's progress (for example **4 / 6 answered**). Each student sees their own team's progress.
   - Answers stay hidden until you reveal them. Locked answers can't be changed unless you use **Reopen team** or **Reopen submissions**.
   - The optional timer counts down on every screen, and when it runs out, submissions lock.
3. **Reveal answers** shows how each team answered: vote counts for multiple choice and true/false, or the most common answer for other types. Open **Every student's answer** to see each student's answer by name.
4. **Show correct answer** highlights the right answer, scores everyone automatically, and shows each team's points.
   - **A team's points come from its members' average score.** Every student who's connected counts, so a student who doesn't answer counts as zero. That keeps everyone participating.
   - Use **Count as correct** next to any student (handy for an unusual typed answer that's still right), or **Mark all correct / Mark wrong / −1 / +1** on a team's card.
5. **Continue to the board** returns to the board and moves to the next team. Nothing advances on its own.

## Points
- Quick questions (multiple choice, true/false, type the answer): **2 points**. Drag questions (word bank, order, match, sort): **3 points**. Part 6 bonus questions: **5 points**.
- Partly correct drag answers earn partial points.
- **Challenge ×2 spaces:** the first team to reach each new part triggers double points for everyone.
- The team that landed on the space earns **+1 bonus point** if they're 80% correct or better.
- **Plot Twists** move teams or award points. Finishing earns **+5, +3, then +1**.

## Teams & roles
- Students are placed on teams automatically so teams stay even, and they're **locked in**. Refreshing or rejoining with the same name puts them back on their team.
- Roles are extra jobs on top of answering. Everyone still answers every question. The dice roller changes every roll, and the question reader and spokesperson change every question, so no one repeats the same job back to back.
- Absent students are skipped. A student who closes the game drops off their team's count within about 15 seconds, so their team isn't penalized.
- Open **Teams & roles** to see everyone, change any role, turn student rolling on or off, or remove a student (✕ twice).

## Good to know
- The game saves as you play. If you refresh, the board, scores, and teams come back, and students reconnect on their own with their answers kept.
- Use Chrome or Edge on the teacher computer, and keep the tab open. Students connect straight to it through the free PeerJS service. Test with one student device on the school network before class.
- Works on computers, Chromebooks, tablets, and phones. Every drag question also works by tapping a card, then tapping where it goes.
