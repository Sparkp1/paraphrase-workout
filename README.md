# ⏱️ Paraphrase Workout

Turn paraphrasing into a mental workout. Paste a paragraph, rewrite it in your own words, and the app times you, measures your speed, and tracks your progress over time.

**▶ Try it here:** https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/

No sign-up, no installation. It runs entirely in your browser.

---

## What it does

- **A timer pinned to the top of the screen** that starts as soon as you begin typing
- **Idle detection**, so a coffee break doesn't count against you
- **Live stats while you write**: typing speed, pace, length, backspaces, and how much of the original wording you kept
- **A quick check-in** after each chunk, where you rate difficulty and focus from 1 to 5
- **Instant results** comparing that chunk with your average and your personal best
- **A dashboard** with progress charts, your best time of day, a day streak, and your full history
- **CSV export** so you can back up your data or analyze it in Excel or Google Sheets

---

## How to use it

1. **Paste** the paragraph you want to rewrite into the **Source chunk** box on the left.
2. *(Optional)* Give it a **label**, like "Chapter 2, paragraph 4".
3. **Start typing** your version in the **Your paraphrase** box. The timer starts automatically.
4. When you're done, click **Finish** or press **Ctrl + Enter** (**Cmd + Enter** on Mac).
5. **Rate** how hard the chunk was and how focused you felt.
6. **Check your results**, copy your paraphrase, and click **Start next chunk**.

Open the **Dashboard** tab anytime to see how you're improving.

---

## What the numbers mean

| Stat | What it tells you |
|---|---|
| **Active time** | Time spent actually working. Pauses longer than your idle limit aren't counted. |
| **Idle time** | Time when you stopped typing for longer than the idle limit (1 minute by default, and you can change it). |
| **Source pace** | Words of the *original* text you get through per active minute. This is the main score, because it captures thinking and typing together. |
| **Adjusted pace** | Source pace with credit for difficulty: +10% per point above 3, −10% per point below. This keeps hard chunks from looking like setbacks. |
| **Typing speed** | Words *you* wrote per active minute. |
| **Length vs source** | How long your version is compared with the original. 100% means the same length. |
| **Backspaces** | How often you deleted while writing, which shows how much you revise as you go. |
| **Shared phrasing** | The share of your three-word phrases that also appear in the original. **Lower is better**, because it means you truly rewrote it. |

> 💡 **Tip:** Try to get faster while keeping shared phrasing low. Speed that comes from copying doesn't count!

---

## Where is my data saved?

Your sessions are saved **in your own browser** on your own device. Nothing is sent to a server, and nobody else can see your stats. The text you paste is never stored in your history, only the numbers.

Some things to keep in mind:

- If you **clear your browser data**, or switch to a **different browser or computer**, your history won't be there.
- Use **Export CSV** on the Dashboard now and then to keep a backup.
- Your in-progress text is saved as you type, so an accidental refresh won't lose your writing. The timer does reset on refresh, though.

---

## Using it offline

You can also download `index.html` and just double-click it to open it in your browser.

The timer and tracking work offline. The **charts** and **fonts** load from the internet, so without a connection the dashboard charts won't appear and the app will use your system fonts instead.

---

## Built with

- HTML, CSS and JavaScript in a single file
- [Chart.js](https://www.chartjs.org/) for the dashboard charts
- [Google Fonts](https://fonts.google.com/): Barlow, Barlow Condensed and Source Serif 4

It supports light and dark mode automatically and works on phones too, although it's best on a computer with a keyboard.
