# Cosmic Ask-Out Journey

This repository contains a single-file interactive webpage (`index.html`) with a cosmic theme and mini-games.

## What is included
- Intro screen with name personalization
- Mini-game 1: star click collection
- Mini-game 2: constellation connect puzzle
- Mini-game 3: memory match cards
- Final personalized ask-out message flow

## Do I have to create it locally in Visual Studio and then push?
Short answer: **yes, usually**.

- GitHub is where your code is stored.
- You normally **edit files on your computer** (Visual Studio Code, terminal, etc.), then `git add`, `git commit`, and `git push`.
- You *can* edit directly on GitHub.com for tiny changes, but for this project (HTML/CSS/JS), local editing is easier.

## Put this into your GitHub repo (`Rupali2930/2026`)

If you want this code in `https://github.com/Rupali2930/2026`, run these commands on your machine:

```bash
git clone https://github.com/Rupali2930/2026.git
cd 2026
```

Then copy `index.html` and `README.md` into that folder, and commit/push:

```bash
git add index.html README.md
git commit -m "Add interactive cosmic ask-out page"
git push origin main
```

If your default branch is `master` instead of `main`, use:

```bash
git push origin master
```

## How to open it locally

### Option 1: Open directly
1. Go to this folder.
2. Double-click `index.html`.

### Option 2 (recommended): Run a local server
From this repository root:

```bash
python3 -m http.server 4173
```

Then open:

- `http://127.0.0.1:4173`

## How to check it works
1. Enter a name on the first screen.
2. Click **Start the journey**.
3. Complete the three mini-games in order.
4. Confirm the **Reveal final message** button unlocks after finishing memory match.
5. Confirm the final screen shows the personalized message using the entered name.

## Quick smoke check commands

```bash
python3 -m http.server 4173
```

In another terminal:

```bash
curl -I http://127.0.0.1:4173
```

Expected: `HTTP/1.0 200 OK` (or equivalent `200` response).
