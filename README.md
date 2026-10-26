# 🧩 Digital Jigsaw Table

![Version](https://img.shields.io/badge/version-v1.0-blue.svg)
![Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen.svg)
![Platform](https://img.shields.io/badge/platform-Browser-darkred.svg)
![Language](https://img.shields.io/badge/language-TR%20%7C%20EN-blue.svg)
![Offline](https://img.shields.io/badge/works-offline-lightgrey.svg)
![Pieces](https://img.shields.io/badge/pieces-12%20to%2020%2C000-orange.svg)

Digital Jigsaw Table turns any picture into a jigsaw puzzle that you solve on a big virtual table. Pick one of the built-in pictures or drop in your own photo, choose how many pieces you want — from a quick 24-piece puzzle up to a monster with 20,000 pieces — spread them out and start building. The entire application is a **single HTML file** — no server, no installation, no build step, no internet connection required.

## 🚀 Key Features

* ✅ **Zero setup:** One `.html` file. Double-click and it runs. No Python, PHP, Node or web server needed.
* ✅ **Your own picture:** Choose a file, drag and drop it onto the page, or paste it from the clipboard. JPG, PNG, WebP and GIF are supported. Pictures up to 5000 px on their longest side (3600 px on phones) are used as they are; larger ones are scaled down.
* ✅ **Any piece count:** One-tap presets (24, 48, 100, 200, 300, 500, 750, 1000, 1500, 2000, 3000) or type any number from 12 to 20,000. The grid is chosen to match your picture's proportions.
* ✅ **Real jigsaw pieces:** Every puzzle gets its own random set of tabs and blanks, drawn with a soft bevel. Each piece shows only its own part of the picture.
* ✅ **Snap & merge:** Drop a piece near its neighbour or its place in the frame and it snaps in. Joined pieces move together as one group.
* ✅ **Infinite table:** Pan and zoom freely with the mouse wheel, drag, keyboard or a two-finger pinch. The table scrolls on its own when you drag a piece to the screen edge.
* ✅ **Tidy tools:** Separate the edge pieces, sort the loose pieces by colour, or shuffle them across the tray again.
* ✅ **Helpers:** A box-picture preview, a faint guide image in the frame, a live progress bar and a timer.
* ✅ **Resume anywhere:** Progress is saved automatically after every move. Keep up to six unfinished puzzles at once and continue them whenever you like.
* ✅ **Portable saves:** Save any puzzle — including its picture — to a single `.json` file and open it on another device with **Continue from file**.
* ✅ **Heavy-load warnings:** Before you start a very large puzzle, the app tells you how much memory it is expected to use and whether your device is likely to struggle.
* ✅ **Bilingual:** Full Turkish and English interface, switchable at any time. The default follows your browser language.
* ✅ **Two themes:** A light theme and a pure-black OLED theme for night-time play.
* ✅ **Phone and tablet ready:** Touch dragging, pinch to zoom and a layout that fits small screens.
* ✅ **Storage control:** See how much browser storage your saves use and clear them all with one confirmed click.

## 💻 Usage

Download `digital-jigsaw-table.html` and open it in any modern browser. That is the whole installation process.

1. Pick a sample picture or add your own.
2. Choose the number of pieces.
3. Press **Start puzzle** and drag the pieces from the tray into the frame.

> [!NOTE]
> Your progress is saved automatically in the browser's own storage (IndexedDB). Because each browser keeps its own separate storage, progress does not travel between browsers or devices on its own — use **Save to file** and **Continue from file** to move it.

> [!TIP]
> For use on a phone, host the file on any static host (GitHub Pages, Netlify, Cloudflare Pages) and use "Add to Home Screen". This is far more practical than opening a local file on mobile, and it keeps Safari from clearing your data after 7 days of inactivity.

### Moving your progress to another device

1. While playing, click the **download** button in the top bar (**Save to file**). On the start screen you can also use the download button next to any unfinished puzzle.
2. Copy the downloaded `.json` file to the other device.
3. Open the app there and click **Open save file** (or **Continue from file**) on the start screen.

Everything is restored exactly: piece positions, joined groups, elapsed time, and the picture itself. If the same puzzle already exists on that device and has progressed further than the file, the file is added as a separate save instead of overwriting it — you can never lose newer progress by accident.

### Controls

| Action | Mouse | Touch |
|---|---|---|
| Move a piece or group | Drag it | Drag it |
| Move around the table | Drag an empty spot, or right / middle-button drag | Drag an empty spot |
| Zoom | Mouse wheel, `+` / `-` | Pinch with two fingers, `+` / `−` buttons |

| Key | What it does |
|---|---|
| `F` | Show the whole table |
| `R` | Go to the picture area |
| `G` | Toggle the faint guide picture in the frame |
| `P` | Toggle the box-picture preview |
| `+` / `-` | Zoom in / out |
| Arrow keys | Pan the table |
| `Esc` | Close the preview and open menus |
| `D` | Show or hide the performance panel (see below) |

## 📸 Screenshots

<img width="2560" height="1356" alt="Screenshot_20261026_134224" src="https://github.com/user-attachments/assets/c88ee3a0-cf30-4726-83d1-78a6e82735c2" />  

<img width="2543" height="1312" alt="Screenshot_20261026_140956" src="https://github.com/user-attachments/assets/8e827923-f71c-4bcd-aeac-d00240af6906" />

<img width="2560" height="1313" alt="Screenshot_20261026_135621" src="https://github.com/user-attachments/assets/1a0cb003-1037-4fa4-af96-516b42eea433" />

<img width="2560" height="1309" alt="Screenshot_20261026_140610" src="https://github.com/user-attachments/assets/4462da0f-bd27-4aa5-91ff-5b5aa1fbcc98" />


### Performance panel

If the game feels choppy on your machine, press `D` while playing. A small panel shows the current frame rate, the time spent drawing, the piece and sprite sizes, the canvas size and the graphics adapter your browser reports. If it shows a software renderer (for example *SwiftShader* or *Microsoft Basic Render Driver*), hardware acceleration is turned off in your browser. On laptops with two graphics chips, also check that the browser is allowed to use the fast one (Windows: *Settings → System → Display → Graphics*).

## 🔒 Data & Privacy

No accounts, no tracking, no network requests — not even web fonts; the interface uses your system's own font. Your picture never leaves your device. Everything lives in your browser's local storage, and the save file is a plain JSON document that contains the piece positions and your picture (as a JPEG, base64-encoded).

## 📋 Requirements

Any modern browser: Chrome, Edge, Firefox, Safari, or their mobile versions. There is nothing else to install. For puzzles above roughly 10,000 pieces a desktop or laptop computer is recommended.

---

Copyright (c) 2026 Oktay Mercan

---

AI used.
