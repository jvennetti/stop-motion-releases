# Hop for testers

Hop is the new build of the stop-motion app. It replaces the old "Stop Motion" app
(version 0.2.0) and uses the same project folders.

## Install

1. Download the newest `Hop-<version>-win64-setup.exe` from
   https://github.com/jvennetti/stop-motion-releases/releases/latest
2. Run it. Windows may show "Windows protected your PC". Click **More info**, then
   **Run anyway**. The installer is not signed yet, which is why Windows asks.
3. Click through. No admin password is needed; Hop installs for your user only.
4. A "Hop" shortcut lands on the desktop and in the Start menu.

The old Stop Motion 0.2.0 stays installed unless you tick **Remove the old Stop
Motion 0.2.0** in the installer. Either way your projects and settings stay.

## Your projects

Both apps use the same folder: `Documents\Stop Motion Projects`. A shot you made in the
old app opens in Hop. Do not keep the same shot open in both apps at once.

## Updates

Hop checks for a newer version when it starts and shows a small box in the corner when
there is one. Click Update; Hop installs it and comes back.

## What to tell Joshua

When something goes wrong, send:

- what you did, what you expected, what happened instead
- a screenshot if the screen looked wrong
- the log file: press Win+R, paste `%APPDATA%\stop-motion-app`, press Enter, and send
  `log.txt`

Crashes are the obvious thing to report. Annoyances count too: "the buttons do nothing"
was a real bug, found by a tester who said exactly that.

## Cameras

Webcams work out of the box. Canon EOS cameras connect over USB (plug the camera in,
set a manual mode on the dial, pick it under Camera > Source), but this build has not
been tried with a camera body yet. If you try it, tell Joshua how it went either way.
