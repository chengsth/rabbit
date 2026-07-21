# 🐰 Rabbit & Memo

A tiny **website** of pastel games and stories starring Rabbit and Memo.
Open `index.html` and you land on a home page with three things to do:

| Page | File | What it is |
|------|------|------------|
| 🎮 **Tower Defense** | `game.html` | Buy guns, place defenders, survive 10 waves. |
| 🔤 **Picture Word Book** | `picture-book.html` | Six mini word books; tap a picture to hear the word. |
| 📚 **The 153 Stars** | `chapter-book.html` | A bedtime chapter book in 153 illustrated chapters. |

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
