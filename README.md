# 🐰 Rabbit & Memo

A tiny **website** of pastel games and stories starring Rabbit and Memo.
Open `index.html` and you land on a home page with three things to do:

| Page | File | What it is |
|------|------|------------|
| 🎮 **Tower Defense** | `game.html` | Buy guns, place defenders, survive 10 waves. |
| 🎈 **Number Balloons** | `maths.html` | Pop the balloon with the right answer to the sum. |
| 🔤 **Picture Word Book** | `picture-book.html` | Six mini word books; tap a picture to hear the word. |
| 📚 **The 153 Stars** | `chapter-book.html` | A bedtime chapter book in 153 illustrated chapters. |
| 🥞 **The Pancake Song** | `song.html` | A sing-along song the browser plays — as pop or as jazz. |

Every page has a 🏠 button in the corner to hop back home. It's all plain
self-contained HTML — no build step, no dependencies, no internet required once
a page is open.

## 🎮 Tower Defense (`game.html`)
A cute pastel tower defense game.
1. Pick a gun from the shop (Pebble Blaster, Carrot Launcher, Jelly Cannon, or Star Blaster).
2. Tap a glowing **+** pad to place a defender there.
3. Press **Start Wave**. Defenders shoot enemies automatically.
4. Earn coins for every enemy popped; lose a life if one reaches the base.
5. Tap a placed defender to sell it and rework your setup.

## 🎈 Number Balloons (`maths.html`)
A maths game where every answer floats by on a balloon. A sum appears at the top,
four balloons drift up from the grass, and you pop the one with the right answer
before it sails off the sky.

- Pick what to practise: **🎲 Mix**, **➕ Adding**, **➖ Taking away**, **✖️ Times**
  or **➗ Sharing**.
- Pick **how hard** you want it: **🍼 Gentle**, **🙂 Normal**, **🔥 Hard** or
  **💀 Extreme**. This sits on top of your age, so you can crank the game up
  without pretending to be older, and your choice is remembered.
- You have **three hearts**. A wrong pop costs one, and so does letting the right
  balloon escape — but the sum stays up so you can try again.
- Every 4 right answers is a **new level**: bigger numbers and faster balloons.
  In Mix, times sums join in once you get going, and sharing sums after that.
- Once the plain sums stop being a challenge, harder shapes appear: **missing
  number** puzzles like `7 + ? = 12` that you have to work backwards, and
  **three-number** sums like `4 + 5 + 2`. Higher up, the wrong answers stop being
  obvious and crowd in right next to the right one.
- A **streak** of right answers in a row is worth bonus points, and your best
  score is saved.
- For little ones the sum is also drawn in **carrots, strawberries and flowers**
  to count, and 🗣️ reads the sum aloud (on by default for ages 7 and under).
- Tap a balloon, or press <kbd>1</kbd>–<kbd>4</kbd> for the balloons left to right.

The sums start where the **🎂 Choose Age** page says they should — age 5 gets
small adding and taking away, age 45 gets times tables, age 100 gets big numbers
fast — and the **How hard?** setting multiplies that. Age 8 on Normal starts with
sums to about 10 and a leisurely 13 seconds a balloon; the same age on Extreme
starts with times and sharing sums and 9 seconds, and by level 10 you are down to
under 8 seconds.

## 🔤 Picture Word Book (`picture-book.html`)
A picture-and-word book for little learners, with six mini-books you switch
between using the tabs at the top:

- **ABC** — the alphabet A to Z (A is for Apple, B is for Butterfly, …)
- **Animals**, **Food**, **Colors**, **Shapes** — themed first words
- **Numbers** — a counting book (page 3 shows ⭐⭐⭐ = *Three*)

**Tap a picture** (or press <kbd>Space</kbd>) to hear the word read aloud, turn
pages with the ◀ ▶ buttons / arrow keys / a swipe, or press **Read to me** to
auto-play the whole book.

## 📚 Chapter Book — *Rabbit & Memo and the 153 Stars* (`chapter-book.html`)
A full bedtime chapter book: one continuous story told in **153 short chapters**,
organised into 9 parts. Rabbit, Memo, and their friends journey across meadow,
caves, clouds, and snowfields to gather 153 fallen star-lights.

- Every chapter has its own little **picture** above the words.
- **Table of Contents** to jump to any chapter, grouped by part.
- **Turn pages** with the ◀ ▶ buttons, the arrow keys, or a swipe on touch.
- Your place is **saved automatically** — close the book and pick up where you left off.
- Optional **Read this chapter aloud** button.

## 🥞 The Pancake Song (`song.html`)
A sing-along song about making pancakes. Nothing is downloaded and there is no
audio file — the browser *plays the band itself* with the Web Audio API, so the
page works offline like everything else here.

The same tune comes with **two arrangements**, and you can swap between them
whenever you like, even in the middle of the song:

- 🎤 **Pop** — 112 beats a minute, straight eighths, bright synths, a clap on
  every 2 and 4, and a four-on-the-floor kick drum.
- 🎷 **Jazz** — 132 beats a minute with a **swung** beat, brushes and a ride
  cymbal, a walking bass line, and seventh chords instead of plain triads.

While it plays:
- The words light up **one syllable at a time**, in time with the tune.
- A stack of pancakes bounces on the beat, grows taller through the chorus, and
  does a somersault every time the song says *flip*.
- **Tap any line** in the words underneath to start singing from there.
- Turn on **🎙️ Words out loud** to have the line read to you as it comes around
  (it uses the same reading voice you picked in the other books).
- <kbd>Space</kbd> starts and stops it.

The song is about two and a half minutes long as pop, and a bit over two as jazz.

## Run it locally
Double-click `index.html` to open the home page in Chrome (or any browser), then
click a card. Because the pages link to each other with plain relative links, the
whole site works straight off your disk — no server needed.

## Put it online (GitHub Pages)
To get a real website URL you can open in Chrome from anywhere:
1. In this repo, go to **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Pick the **main** branch and the **/ (root)** folder, then **Save**.
4. Wait a minute, then open the URL GitHub shows you
   (something like `https://chengsth.github.io/rabbit/`).

That URL opens the home page in any browser — phone, tablet, or computer.
