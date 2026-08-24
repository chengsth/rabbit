# 🐰 Rabbit & Memo

A tiny **website** of pastel games and stories starring Rabbit and Memo.
Open `index.html` and you land on a home page with a handful of things to do:

| Page | File | What it is |
|------|------|------------|
| 🎮 **Tower Defense** | `game.html` | Buy guns, place defenders, survive 10 waves. |
| 🛡️ **S.W.A.T. Creature Cleanup** | `swat.html` | Walk, aim, and clear the creatures out of eight zones. |
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

## 🛡️ S.W.A.T. Creature Cleanup (`swat.html`)
You are **Officer Rabbit** of the S.W.A.T. squad, and wobbly slime creatures have
moved into the building. Your mission is to clear every last one of them out of
all **eight zones**, from The Lobby down to The Nest — and then face the crowned
**Big One** herself. Creatures pop into a puff of bubbles when you get them.

- **Walk** with <kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> or the arrow keys.
- **Shoot** by holding the mouse button (or <kbd>Space</kbd>); <kbd>P</kbd> pauses.
- **Four guns**, swapped with <kbd>1</kbd>–<kbd>4</kbd>: the Sidearm never runs out,
  the Scatter fires six pellets, the Rapid is a stream of little darts, and the
  Zapper punches straight through a whole line of creatures.
- Popped creatures leave behind **ammo boxes** and sometimes a **health kit**.
- **Auto-aim** is on by default for younger players — turn it off in the panel for
  a proper challenge.
- **On a tablet**, drag anywhere on the left half of the screen to walk and hold
  the right half to shoot.

Six kinds of creature turn up: green **blobs**, quick purple **zippers**, chunky
blue **brutes**, orange **spitters** that lob slime from a distance, pink
**splitters** that break into two splitlings, and the boss, who keeps calling for
backup. Hide behind the crates — neither your shots nor their slime go through
them. The game uses the age from the **Choose Age** page too.

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
