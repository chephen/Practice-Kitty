# Practice Kitty

A piano practice companion for young kids. A friendly kitty listens while they
practice, gives quick encouragement, and hands out treats when the day's songs
are done, so a busy parent doesn't have to sit through every session.

## What's here

- `index.html` — the whole app, a single-file web app. Open it in a browser,
  or serve it from any static host. Add it to an iPad/iPhone home screen to
  use it like an app.

## How it works

- **Practice**: the parent's list of songs for the week. The kitty listens
  through the microphone (Web Audio, on-device only) and counts run-throughs,
  checks for a steady beat, and notices stuck spots. No audio is ever recorded,
  stored, or sent anywhere; only numbers like minutes and run-through counts
  are kept, on the device.
- **Kitty**: pet, feed, and dress up the kitty with fish and stars earned from
  practice.
- **Grown-ups**: behind a simple gate — upload the week's music sheet photo,
  edit songs, and see a practice summary.

## Privacy

Everything stays in the browser's local storage on the device. There is no
server, no account, and no audio recording. See the project plan for the
COPPA reasoning.
