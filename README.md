# Open Mic

Mix your microphone with the audio your Mac is playing, and use both as a single
input device — for transcription tools, AI assistants, or anything else that
reads one microphone.

**[openmic site](https://tkkrtky.github.io/OpenMic/)** ·
**[Download](https://github.com/TKKRTKY/OpenMic/releases/latest)** ·
[日本語](https://tkkrtky.github.io/OpenMic/ja/)

macOS 14.2 or later. Signed with a Developer ID and notarized by Apple.

---

## What is in this repository

The landing page, and the released package under
[Releases](https://github.com/TKKRTKY/OpenMic/releases).

**The application source is not published here.** Issues and feedback are
welcome regardless — the app has a **Send Feedback** menu item that opens a new
issue with the diagnostics already filled in.

```
index.html      English
ja/index.html   Japanese
assets/         icon, figures, stylesheet
```

## Reporting a problem

Please use [Issues](https://github.com/TKKRTKY/OpenMic/issues). The most useful
reports say which app you were using and which half of the audio was missing —
your voice, or the other side. The menu bar meter shows this directly: the left
bars are your microphone, the right bars are your Mac.

## Uninstalling

```sh
sudo "/Library/Application Support/OpenMic/uninstall.sh"
```

Removes the app, the audio driver and the background service, then checks that
nothing was left behind.
