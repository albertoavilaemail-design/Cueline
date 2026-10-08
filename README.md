# Cueline Prompter

A phone-first teleprompter: Auto Scroll, Voice Follow, and front-camera recording.

## Put it online (GitHub Pages, about 5 minutes)

Recording and Voice Follow need the app to run from its own https address. GitHub Pages gives you one for free.

1. On github.com, create a new public repository, for example `cueline`.
2. Click **Add file → Upload files** and drag in everything from this folder: `index.html`, `manifest.webmanifest`, `sw.js`, and the three `icon` files. Commit.
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute your app is live at `https://<your-username>.github.io/cueline/`.

## Put it on your phone

1. **iPhone:** open that address in Safari and bookmark it. You can also add it to your Home Screen; the icon opens it in a Safari tab, which floating mode needs.
2. **Android:** open it in Chrome.

## First test take

1. Open the sample script and tap the text. Auto Scroll should start after a 3-second countdown.
2. Open settings (the sliders icon), switch to **Voice Follow**, and allow the microphone. Read a few lines and watch it follow.
3. Tap **Float**, make the floating prompter, and record a 10-second test with the Camera app.

## Floating mode (record with the real Camera app)

1. Open a script and tap **Float** at the bottom of the reading screen (or choose **Float over camera** from a script's ⋯ menu).
2. Pick a text size and tap **Make floating prompter**. It turns your script into a scrolling video at your current speed.
3. Tap **Open floating window**, swipe home, and open **Camera**. Drag the window to the top edge, near the lens.
4. Start recording, then tap play in the floating window.

Speed is fixed once the video is made, and Voice Follow doesn't work here. Use the window's pause and 15-second skip buttons. To change speed, set it in the app and make it again. Needs iOS 16.4 or later, and it must run in a Safari tab: iPhones block floating windows for websites opened as Home Screen apps.

## Good to know

- Scripts and settings are saved on the phone, in this browser. Use **⋯ → Export backup** now and then.
- Voice Follow uses the browser's speech recognition (Apple's on iPhone, Google's on Android). It needs internet and is less reliable in Safari than in Chrome.
- Start a line with `#` in the editor to make a section you can jump to.
