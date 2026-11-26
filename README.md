# REFLEX
### HOW FAR CAN YOUR MIND GO?

<p align="center">
  <img src="./assets/hero.svg" alt="REFLEX — The Ultimate Challenge Experience" width="100%">
</p>

<p align="center">
  <strong>FIVE CHALLENGES. FIVE SKILLS. ONE MIND.</strong>
</p>

<p align="center">
  <a href="REPLACE-WITH-YOUR-DEPLOYED-URL"><strong>PLAY REFLEX LIVE</strong></a>
  &nbsp; • &nbsp;
  <a href="#the-five-challenges">EXPLORE GAMES</a>
  &nbsp; • &nbsp;
  <a href="#getting-started">GET STARTED</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Web-111318?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/Games-05-C8FF5E?style=for-the-badge" alt="Five games">
  <img src="https://img.shields.io/badge/Dependencies-Zero-111318?style=for-the-badge" alt="Zero dependencies">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT license">
</p>

---

## 01 — Introduction

**REFLEX** is a collection of five interactive mental and reaction-based challenges designed to test different aspects of human performance.

It is not another ordinary collection of browser games.

Every challenge focuses on a different ability, from split-second reactions to pattern recognition, concentration, observation and logical thinking.

Whether you're trying to beat your personal record or discover your strongest skill, REFLEX gives you a reason to try again.

**No accounts. No downloads. No unnecessary complexity. Just you and the challenge.**

## 02 — The Five Challenges

<p align="center">
  <img src="./assets/games.svg" alt="Five REFLEX challenges" width="100%">
</p>

### 01. DON'T BLINK
**FOCUS & CONCENTRATION**

How long can you maintain your focus?

- Choose between 30, 60 and 90-second challenges.
- Keep your eyes open throughout the countdown.
- Report a blink using the on-screen button or Space key.
- Experience an entertaining detective-style Hindi voice-over when you lose.
- Beat your previous concentration record.

*Challenge: Your focus is your only advantage.*

### 02. REACTION ZERO
**REFLEXES & RESPONSE TIME**

Every millisecond matters.

- Five rounds per session.
- Random waiting periods between 2 and 7 seconds.
- React immediately when the screen turns green.
- Early clicks count as false starts.
- Track reaction time in milliseconds.
- Automatically calculate your average and best reaction time.

*Challenge: How fast can you react?*

### 03. MEMORY MATRIX
**MEMORY & PATTERN RECOGNITION**

Watch carefully. Remember everything.

- Watch a sequence of illuminated tiles.
- Reproduce the exact sequence.
- Each successful level adds another tile.
- Progress through 3×3, 4×4 and 5×5 grids.
- Three lives per session.
- Track your highest level.

*Challenge: How much can your memory handle?*

### 04. IMPOSSIBLE COUNT
**OBSERVATION & ACCURACY**

Find the pattern inside the chaos.

- Identify a specific geometric shape.
- Count shapes while they move and rotate.
- Deal with changing visual distractions.
- Eight progressively difficult rounds.
- Earn additional points for answering quickly.
- Track your overall accuracy.

*Challenge: Can you trust your observation?*

### 05. LOGIC LOCK
**LOGICAL THINKING & REASONING**

Every pattern has an answer.

- Solve generated number sequences.
- Recognize mathematical patterns.
- Complete symbol sequences.
- Choose from four possible answers.
- Work against a countdown timer.
- Build consecutive correct-answer streaks.

*Challenge: Think clearly under pressure.*

---

## 03 — Gameplay Experience

REFLEX is designed around a simple gameplay philosophy:

**Understand → Prepare → Play → Score → Improve**

Every challenge includes:

- Dedicated instruction screen.
- Interactive gameplay environment.
- Live score and progress indicators.
- Appropriate countdown timers.
- Immediate feedback.
- Game-over and result screens.
- Performance ratings.
- Restart functionality.
- Personal record tracking.

The goal is to make every attempt feel meaningful.

## 04 — Scoring System

Every game uses its own scoring logic.

| Game | Scoring |
|---|---|
| Don't Blink | 10 points per second survived, plus 100 for completion |
| Reaction Zero | Up to 1,000 points per successful round, based on reaction time |
| Memory Matrix | 100 × level for each cleared level |
| Impossible Count | 100 points per correct answer plus time bonus |
| Logic Lock | 100 points per correct answer plus time and streak bonuses |

### Performance Ratings

Every completed session receives one of four performance ratings:

| Rating | Performance |
|---|---|
| Keep Training | Below 40% |
| Sharp | 40–69% |
| Elite | 70–89% |
| Legendary | 90–100% |

Your goal is simple: improve your performance with every attempt.

## 05 — Personal Dashboard

Your progress is displayed directly on the homepage.

### Statistics

- Total games played.
- Best reaction time.
- Highest memory level.
- Overall answer accuracy.
- Personal best for every challenge.
- Last eight game results.

### Local Data Storage

REFLEX uses browser `localStorage` to preserve your progress.

Your statistics remain available when you revisit the website using the same browser and storage profile.

No account or remote database is required.

You can also reset your statistics whenever you want.

## 06 — Design Philosophy

REFLEX follows a minimal, premium visual direction.

The interface prioritizes readability, spacing, contrast and gameplay clarity.

### Visual Identity

| Design Element | Value |
|---|---|
| Background | `#090A0C` |
| Secondary Background | `#111318` |
| Cards | `#17191F` |
| Primary Text | `#F5F5F5` |
| Secondary Text | `#92949D` |
| Accent | `#C8FF5E` |

### Interface Principles

- Dark, distraction-free interface.
- Consistent typography.
- Carefully balanced spacing.
- Subtle transitions and animations.
- Responsive layouts.
- Minimal visual noise.
- Clear interactive elements.
- Consistent design across all challenges.

The interface is designed to feel like a polished independent gaming product rather than a generic game template.

## 07 — Technology Stack

REFLEX is built using standard browser technologies.

| Technology | Purpose |
|---|---|
| HTML5 | Structure and markup |
| CSS3 | Layout, animations and responsive design |
| JavaScript | Game mechanics and application logic |
| Canvas API | Dynamic geometric rendering |
| Web Audio API | Synthesized sound effects |
| Web Speech API | Hindi voice-over |
| LocalStorage | Persistent player statistics |

### Zero External Dependencies

The core application does not require:

- React
- Vue
- Angular
- Node.js
- Backend servers
- Database services
- Authentication systems

It runs directly in a modern web browser.

## 08 — Getting Started

You can run REFLEX locally without installing any dependencies.

### Requirements

- A modern web browser.
- Python 3 (optional, for local HTTP serving).

### Option 1 — Open Directly

1. Download or clone the repository.
2. Locate `index.html`.
3. Open it in your browser.

### Option 2 — Local HTTP Server

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/REFLEX.git
```

Enter the project directory:

```bash
cd REFLEX
```

Start a local server:

```bash
python -m http.server 8080
```

Open:

```text
http://localhost:8080
```

That's it. REFLEX is ready to play.

## 09 — Project Structure

```text
REFLEX/
│
├── index.html
│
├── assets/
│   ├── hero.svg
│   └── games.svg
│
├── README.md
│
└── LICENSE
```

The complete application logic, interface and styling are contained in a single HTML file.

## 10 — Browser Compatibility

REFLEX is intended for modern browsers supporting standard HTML5 and JavaScript APIs.

| Feature | Browser Requirement |
|---|---|
| Core gameplay | Modern JavaScript browser |
| Sound effects | Web Audio API |
| Hindi voice-over | Web Speech API |
| Persistent statistics | LocalStorage |
| Shape rendering | Canvas API |

Some features, particularly voice synthesis, depend on browser and operating-system support.

## 11 — Important Notes

- Don't Blink currently uses manual blink reporting. It does not automatically detect blinks through a webcam.
- Audio starts after user interaction.
- Sound can be muted from the navigation bar.
- Hindi voice-over availability depends on installed browser voices.
- Progress is stored locally and may be lost if browser storage is cleared.
- REFLEX does not require an account.

## 12 — Future Roadmap

REFLEX starts with five challenges, but the possibilities are much bigger.

Potential future additions:

- [ ] Webcam-based blink detection.
- [ ] Daily challenge mode.
- [ ] Global leaderboard.
- [ ] Player profiles.
- [ ] Achievement and badge system.
- [ ] Additional difficulty levels.
- [ ] More mini-games.
- [ ] Multiplayer challenges.
- [ ] Daily and weekly statistics.
- [ ] Progressive Web App support.

These are planned possibilities, not currently implemented features.

## 13 — Contributing

Ideas, improvements and bug reports are welcome.

If you want to contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test your implementation.
5. Submit a pull request.

Keep the code clean, the interface consistent and the gameplay enjoyable.

## 14 — License

This project is distributed under the MIT License.

See the `LICENSE` file for details.

---

<p align="center">
  <strong>REFLEX</strong>
</p>

<p align="center">
  FIVE CHALLENGES. FIVE SKILLS. ONE MIND.
</p>

<p align="center">
  <em>Don't just play. Test yourself.</em>
</p>

<p align="center">
  Made with dedication.
</p>
