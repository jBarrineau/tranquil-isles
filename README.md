# Tranquil Isles · Mini Golf

A calm 3D mini golf game made with three.js. There are nine holes on floating islands, and each one is a later time of day, from sunrise to lantern light. It's designed for the iPad.

## How to play

- **Putt:** touch the ball, pull back, and let go. The farther you pull, the harder the putt.
- **Look around:** drag anywhere else on the screen.
- **Zoom:** pinch.
- **Eye button:** shows the whole hole from above.

## Playing together

On the title screen, tap **+** to add up to four players and type in their names. Everyone gets their own coloured ball and takes turns on each hole. Whoever scored best on the last hole tees off first. At the end, the scorecard crowns a winner. The lowest round ever played on the device is kept as the **course record**.

## Things to discover

- **Golden sea stars:** each hole has three. Roll through them to collect them. Some are easy and some sit right next to the pond.
- **The secret isle:** collect 18 sea stars in one round to unlock a hidden tenth hole after Lantern Night. It has moon gates that send your ball to another part of the green.
- **Trick shots:** bank shots, bumper combos, windmill ricochets, lip-ins and long bombs each get a callout.
- **Nail-biters:** when a long putt is about to drop, the game slows down so you can watch it fall.
- **Keepsakes:** 15 little achievements to collect, from *Hole in One* to *Kerplunk!* Tap **✦ Keepsakes** on the title screen to see them.

## Publish on GitHub Pages

1. Create a new repository on GitHub (for example `tranquil-isles`).
2. Upload every file in this folder to the root of the repository, including the hidden `.nojekyll` file.
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute or two the game is live at `https://<your-username>.github.io/tranquil-isles/`.

## Put it on the iPad home screen

Open the link in Safari, tap **Share → Add to Home Screen**. It then opens full-screen with its own icon, like an app.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole game (code, sounds and visuals) |
| `manifest.webmanifest` | App name and icons for the home screen |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | Home-screen icons |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

It loads three.js r128 and Google Fonts from public CDNs, so it needs an internet connection.
