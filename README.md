<p align="center">
  <img src="./assets/hero.svg" alt="FIVE. How far can your mind go? Five tiles in an isometric grid rise and light up one after another." width="100%">
</p>

<p align="center">
  <a href="https://REPLACE-WITH-YOUR-URL"><b>Play FIVE in your browser</b></a>
</p>

FIVE is five short challenges that each test a different part of how you think: reflexes, focus, memory, observation and logic. Every run is scored and rated, and your personal bests are kept on your device. There is no account and nothing to install.

## The challenges

<img src="./assets/games.svg" alt="The five challenges: Don’t Blink, Reaction Zero, Memory Matrix, Impossible Count and Logic Lock, each with a small animated preview." width="100%">

| Challenge | Tests | How it plays |
| --- | --- | --- |
| Don’t Blink | Focus | Hold a stare for 30, 60 or 90 seconds. Press the button the moment you blink and a detective-style Hindi voice-over announces that you've lost. |
| Reaction Zero | Reflexes | Five rounds. After a random wait of 2 to 7 seconds the screen turns green and you tap as fast as you can. Tapping early is a false start and the round restarts. |
| Memory Matrix | Memory | Repeat a growing sequence of tiles. The grid steps up from 3×3 to 4×4 at level 5 and to 5×5 at level 10. You have three lives. |
| Impossible Count | Observation | Count one shape while the others drift, flicker and pulse. Eight rounds, each with more shapes, faster movement and less viewing time. |
| Logic Lock | Logic | Ten generated puzzles built from number and symbol patterns. Pick the missing piece from four answers before the timer runs out. |

## Scoring and stats

Each game has its own score:

- **Don’t Blink** gives 10 points per second you last, plus 100 for finishing.
- **Reaction Zero** gives 1000 minus your reaction time in milliseconds, per round.
- **Memory Matrix** gives 100 points times the level for every level you clear.
- **Impossible Count** gives 100 points per correct count, plus a bonus for answering early.
- **Logic Lock** gives 100 points per correct answer, plus a time bonus and a streak bonus.

Every run ends with one of four ratings: Keep training, Sharp, Elite or Legendary.

The dashboard shows games played, best reaction time, memory level record, overall accuracy, a personal best for each game and your last eight results. All of it is stored in your browser's `localStorage` under the key `five1`. The Reset stats button clears it.

## Run it locally

FIVE is a single HTML file with no build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then go to `http://localhost:8080`.

## Project structure

```
.
├── index.html        the whole game: markup, styles and logic
├── assets/
│   ├── hero.svg      animated header used in this README
│   └── games.svg     animated challenge previews used in this README
└── README.md
```

## Built with

Plain HTML, CSS and JavaScript, with no framework and no dependencies.

- Sound effects are synthesised with the Web Audio API, so there are no audio files.
- Impossible Count is drawn on a `<canvas>`.
- The Don’t Blink voice-over uses the Web Speech API.
- Stats use `localStorage`.

## Notes

- Don’t Blink does not use the camera. It is a manual mode where you report your own blink.
- Audio only starts after your first click or tap, and there is a mute button in the navigation bar.
- The voice-over needs a Hindi voice installed in your browser or operating system. Without one, the line appears as text only.

## Colors

| Role | Value |
| --- | --- |
| Background | `#090A0C` |
| Secondary | `#111318` |
| Card | `#17191F` |
| Primary text | `#F5F5F5` |
| Secondary text | `#92949D` |
| Accent | `#C8FF5E` |
