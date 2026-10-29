# Vision Sling

An Angry Birds–style slingshot game you play with hand gestures through your webcam. Pull back with a fist, aim, and open your palm to launch at the tower of blocks and targets.

Hand tracking runs in the browser using [MediaPipe Hands](https://developers.google.com/mediapipe). If the camera isn't available, you can play with the mouse (hold to pull, release to shoot).

## How to play

- ✊ **Fist** — grab and pull the slingshot back
- ✋ **Open palm** — release and shoot
- Green targets score **200**, blocks score **50**

## Run it

Open `index.html` in a modern browser (Chrome works best) and allow camera access. Some browsers only allow the camera over `https://` or `localhost`, so if it's blocked, serve the folder locally:

```bash
npx serve .
```

## Built with

HTML5 Canvas, vanilla JavaScript, MediaPipe Hands
