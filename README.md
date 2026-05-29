# Animal Match-Up – Task 2 Submission

A single-screen interactive memory card game built for children aged 3–5 years.
Part of the Sprout evaluation tasks (Task 2: Build a mini interactive screen)

## What It Is
Animal Match-Up is a tap-to-flip memory matching game where kids find pairs of hidden animals. A friendly fox named **Milo** guides and cheers the child throughout the session.
- 6 cards face-down, hiding 3 pairs of animals (Round 1)
- 8 cards hiding 4 pairs in Round 2 (slight difficulty bump)
- No timer, no score, no penalty for wrong guesses
- Confetti burst + animal sound on every correct match
- Sticker reward at the end of each round

## Why a 3-Year-Old Would Like It

| Design Choice | Why It Works |
| Tap a card → it flips | Satisfies cause-and-effect curiosity |
| Familiar animals (cat, dog, duck) | Children already love and recognise them |
| Animal sounds on match | Surprise + delight moment |
| Wrong flip = silent, no penalty | Zero frustration, fully independent play |
| Confetti on every match | Dopamine-style reward every 30–60 seconds |
| Milo reacts to everything | Emotional connection, feels like a friend |
| Sticker jar at the end | Gentle habit loop — something to look forward to |

## 5-Minute Engagement Loop

| Time | What Happens |
|---|---|
| 0:00 – 0:30 | Milo intro screen, child taps to start |
| 0:30 – 2:30 | Round 1 — find 3 pairs (cat, dog, duck) |
| 2:30 – 2:45 | Celebration screen, sticker earned |
| 2:45 – 4:30 | Round 2 — find 4 pairs (frog, elephant, lion, rabbit) |
| 4:30 – 5:00 | Final celebration, sticker jar, goodbye screen |

## How to Run Locally

No build step needed. Just open the file in any browser:

# Option 1 — just double-click index.html

# Option 2 — serve locally
npx serve .
# then open http://localhost:300

## Tech Stack

- Plain HTML + CSS + JavaScript (no frameworks, no dependencies)
- Web Speech API for animal sounds
- Canvas API for confetti animation
- Google Fonts (Nunito + Baloo 2)

---

## Interactions & Animations

- Card flip (CSS 3D transform with preserve-3d)
- Match pop animation (scale bounce)
- Wrong match shake animation
- Milo jump animation on every event
- Canvas confetti on match and round completion
- Smooth screen transition

## Project Structure
index.html     ← entire app (HTML + CSS + JS in one file)
README.md      ← this file


