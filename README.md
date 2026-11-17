# Narrative Writing Board Game

A 6-team board game with 27 narrative-writing questions. The teacher hosts the board, and students join from their own devices with a game code.

## Put it on GitHub Pages (one time, about 5 minutes)

1. Sign in at github.com and click **New repository** (the green **New** button).
2. Name it something like `narrative-board-game`. Set it to **Public**. Click **Create repository**.
3. On the next page, click **uploading an existing file**. Drag in `index.html` (and this README if you like). Click **Commit changes**.
4. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*. Set **Branch** to `main` and the folder to `/ (root)`, then click **Save**.
5. Wait 1–2 minutes and refresh the Pages settings. Your site address appears at the top, for example:
   `https://YOUR-USERNAME.github.io/narrative-board-game/`

To update the game later, upload a new `index.html` to the same repository. GitHub Pages republishes it within a minute or two.

## Running the game in class

**Teacher (screen-share this window):**
- Open `https://YOUR-USERNAME.github.io/narrative-board-game/?host`
  (or open the site and click **I'm the teacher**). Bookmark this link.
- The setup screen shows a **game code** and a **join link**. Paste the join link into Zoom chat.
- Name your teams and post the team list. Students pick their team after joining.
- Click **Start the game**.

**Students:**
- Open the join link (or the site, then **I'm a student**). Type the code and their first name, then pick a team.
- When it's their team's turn, a **Roll for your team!** button appears.
- When a question comes up for their team (or a Checkpoint for the whole class), they type an answer and tap **Send**. Answers show up on the teacher's card.
- When the teacher presses **Show the answer**, students see the answer too.

**On your screen during each question:**
- Student answers appear under the question with their name and team. Your team's answers are listed first.
- Click **+1 ★** next to any answer to give stars to that student's team (Part 6 bonus questions give double).
- You can still roll yourself, give stars with the buttons at the bottom of the card, or fix scores on the scoreboard.

## Good to know

- **Keep the teacher tab open and in front.** Students connect directly to your browser. If you close or refresh the page, the game and the code are kept, and students reconnect on their own within a few seconds.
- **New code** (in the "Students join" box) disconnects everyone and makes a fresh code. Use it only if you need to.
- **New game** resets the board, but keeps the same code.
- Chrome or Edge works best for the teacher computer. Students can use any modern browser, Chromebooks and phones included.
- Connections go through the free public PeerJS server (0.peerjs.com). If a school network blocks it, students see "Connection trouble." The board still works on your screen, and students can answer in Zoom chat.
- With a very large class (100+), students on the same team can share one device, or you can keep chat as a backup. Every connected student is a live link to your computer.
- Students can see the answers if they open the page's source code. That's normal for a game that runs entirely in the browser.
