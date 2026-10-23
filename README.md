# Biobuzz Robot Sim

A browser-based FTC robot simulator and 3-day course built around the team code in
[Sparky384/2026-Biobuzz](https://github.com/Sparky384/2026-Biobuzz).

- **Lessons**: 12 lessons over 3 days. Each challenge is checked automatically on the virtual field.
- **Explain my code**: click any line of your OpModes to see what it does, plus an automatic review that flags common FTC bugs.
- **Code**: edit Java and run it on a simulated robot (motors, encoders, IMU, arm, claw, distance and touch sensors).

Everything is one file (`index.html`). It needs no server, no install and no account, and it works offline once loaded.
Your edits and lesson progress are saved in the browser you use.

## Put it on GitHub Pages

1. On github.com, click **New repository**. Name it `biobuzz-sim`, make it **Public**, and click **Create repository**.
2. Click **uploading an existing file**. Drag in `index.html`, `README.md` and `.nojekyll`, then click **Commit changes**.
   (On a Mac, press Cmd+Shift+. in Finder to see the hidden `.nojekyll` file. It's optional.)
3. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then click **Save**.
4. After about a minute the site is live at `https://YOUR-USERNAME.github.io/biobuzz-sim/`.

To update it later, upload the new `index.html` to the same repo. Pages redeploys on its own.

## Using it at school

- It runs in Chrome, Edge, Safari or Firefox, including school Chromebooks.
- If your school blocks `github.io`, download `index.html` (to Google Drive or a USB stick) and open it directly.
  It works the same way from a local file.
- If Google Fonts is blocked, the page falls back to system fonts automatically.
- Progress is saved per browser. If your school browser clears data when you log out, your lesson checkmarks reset,
  but the lessons themselves are always there.

## Controls

Click the field, then use **W A S D** for the left stick, the **arrow keys** for the right stick, **K L J I** for A B X Y,
**Q / E** for the bumpers, **Z / C** for the triggers and **T F G H** for the dpad. A USB or Bluetooth gamepad also works,
and on a touchscreen you can drag the on-screen sticks.

The simulator understands the subset of Java that FTC code usually uses. Always build in Android Studio before trusting code on the real robot.
