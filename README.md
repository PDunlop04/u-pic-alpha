# U-pic

A single-file browser game prototype set on a UVic-inspired campus map. Solve picture-word puzzles to unlock campus buildings, collect map pieces, find hidden treasure, answer campus trivia, and complete daily exploration quests.

## Run locally

Open `index.html` in a browser. If your browser restricts local-file behavior, start a local web server from this folder:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

Level progress, hint count, treasure collection, daily quests, and audio preferences are stored in the browser's local storage.
