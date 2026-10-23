# Classroom Score Tracker

A free, browser-based score tracker designed for classroom use — particularly for projecting live scores during activities, competitions, or team games.

**[Try it live →](https://ironstamp.github.io/scoretracker)**

---

## What is it?

A simple, fullscreen-friendly tool for tracking individual or team scores in real time. Add names manually or import a class list from a CSV file, then use the **+1** and **−1** buttons to keep score. The list re-sorts itself so the leader is always at the top. Designed to look great on a projector.

---

## Features

- **Add names manually** — type a name and press Enter or click Add
- **CSV import** — upload a class list CSV to load all names at once
- **+1 / −1 buttons** — adjust any score up or down (scores never go below zero)
- **Live leaderboard** — highest score at the top, ties sorted alphabetically
- **Countdown timer** — 30 s, 1, 1½, 2 or 5 minutes, or a custom number of minutes, with Start / Pause / Reset and a pop-up when time's up
- **Hide Add People** — collapse the entry panel so the scores fill the screen
- **Remove a person** — take someone off the list without affecting the others
- **Reset all scores** — set everyone back to zero at the start of a new round
- **No installation** — runs entirely in the browser, nothing to install or log in to

---

## How to Use

### Adding students

**Manually:** Type a name in the input field and press **Enter** or click **Add**.

**From CSV:** Choose a file under **Or import from CSV**. Put one name per line. A header row of `Name` is skipped, and quotes around names are removed.

Example CSV format:
```
Name
Alice Smith
Bob Jones
Charlie Brown
```

Each whole line becomes one name, so put first and last names in the same cell (`Alice Smith`, not `Alice,Smith`).

### During an activity

Click **+1** to add a point or **−1** to take one away. The leaderboard re-orders immediately.

To time a round, choose a duration from the timer menu and click **Start**. **Pause** stops the clock; **Reset** puts it back.

### Resetting

- **Remove a student** — click **Rem** on their card
- **Reset all scores to zero** — click the **Reset All** button (a confirmation dialog will appear)

---

## Tips

- Run it in **fullscreen mode** (F11) for the best projection experience
- Works best in Chrome or Firefox
- Scores are stored in memory only — refreshing the page will reset everything, so keep the tab open during your lesson
- For team games, just add team names instead of individual students

---

## Built With

- Vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies
- Designed for 1080p projection screens

---

## Licence

Free to use, share, and adapt for educational purposes.

---

---

## More classroom tools

- [Classroom Manager](https://ironstamp.github.io/classroom-tool): post, schedule and copy Google Classroom courses
- [Group Allocator](https://ironstamp.github.io/group-picker): randomly split a class into groups
- [Tarsia Puzzle Generator](https://ironstamp.github.io/tarsia-generator): printable triangle-matching puzzles
- [Domino Chain Puzzle Generator](https://ironstamp.github.io/domino-puzzle-generator): printable domino-chain matching cards

---

*Made by Paul Carter, mathematics teacher, New Zealand.*
