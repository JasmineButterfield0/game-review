# GameLog

A simple, single-file game review app that runs entirely in the browser.

## Features

- **Search or pick a game** — browse a grid of 24 popular titles, filter by name or genre, or add any game manually
- **Write a review** — 5-star rating, free-text review, optional pros/cons
- **Edit & delete** — manage your reviews from the My Reviews tab
- **Sort reviews** — by newest, oldest, highest rated, or lowest rated
- **No login required** — reviews are saved to `localStorage` and persist across sessions

## Usage

Open `index.html` directly in any modern browser. No build step, no server, no dependencies.

```
open index.html
```

## Files

```
game-review/
├── index.html        # The entire app (HTML + CSS + JS)
├── README.md         # This file
└── conversation.txt  # The chat that created this project
```

## Storage

All data is stored in `localStorage` under the key `gamelog_reviews`. To clear all reviews, run this in the browser console:

```js
localStorage.removeItem('gamelog_reviews')
```
