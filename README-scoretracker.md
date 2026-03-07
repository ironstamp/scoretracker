# Classroom Score Tracker

A free, browser-based score tracker designed for classroom use — particularly for projecting live scores during activities, competitions, or team games.

**[Try it live →](https://yourusername.github.io/score-tracker)**

---

## What is it?

A simple, fullscreen-friendly tool for tracking individual or team scores in real time. Add names manually or import a class list from a CSV file, then tap each name to add a point. Designed to look great on a projector.

---

## Features

- **Add names manually** — type a name and press Enter or click Add
- **CSV import** — upload a class list CSV to load all names at once
- **One-tap scoring** — click any name card to increment their score by 1
- **Projection layout** — grid layout with large text, readable from across a classroom
- **Responsive grid** — automatically adjusts columns to fit everyone on screen
- **Reset individual scores** — remove or reset any student without clearing the whole class
- **Reset all scores** — one-click reset of all scores at the start of a new round
- **No installation** — runs entirely in the browser, nothing to install or log in to

---

## How to Use

### Adding students

**Manually:** Type a name in the input field and press **Enter** or click **Add**.

**From CSV:** Click **Upload CSV** and select a file. The CSV should have one name per row — either a single column of names, or firstname and lastname in separate columns (they will be joined automatically).

Example CSV format:
```
Alice
Bob
Charlie
```
or
```
Alice,Smith
Bob,Jones
Charlie,Brown
```

### During an activity

Click a student's card to add 1 point to their score. The score updates immediately and is visible to the class on the projector.

### Resetting

- **Remove a student** — click the ✕ on their card
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

*Created by a mathematics teacher at St Paul's Collegiate School, Hamilton, New Zealand.*
