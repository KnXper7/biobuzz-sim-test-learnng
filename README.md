# Biobuzz Playground

Two sections in one page:

- **YT Course**: one folder per video of Brogan Pratt's 27-part "Learn Java for FTC" series. Each folder starts with your finished code from the previous video (press *Finished this video → next* to carry it over). Test on a virtual test bench (touch sensor, DC motor, servo, distance, color, potentiometer, IMU, LEDs, gamepad rumble) or a practice field for the drivetrain videos.
- **BIOBUZZ Arena**: the full 2026-27 game.

The arena is a browser playground for FTC team [Sparky384/2026-Biobuzz](https://github.com/Sparky384/2026-Biobuzz): your team's Java
runs on a virtual robot in the 2026-27 **BIOBUZZ** arena, laid out and scored per the Competition Manual (TU06).

- **Arena**: HIVE structure with two tipping HIVES, 4 FLOWERS, GARDENS, LOADING ZONES, 40 POLLEN and 16 NECTAR staged per §10.3.1.
- **Robot**: drivetrain plus intake, flywheel shooter, feeder, hood servo and color sensor (edit them in *Robot setup*).
- **Match**: 30 s AUTO, 8 s transition, 2:00 TELEOP, live scoring, ranking-point progress, and the main fouls (G407, G408, G410, G418, G426).
- **Code**: edit Java in the browser. `BiobuzzAuto` (tips the HIVE, scores 36) and `BiobuzzTeleOp` are included as examples.
- **Explain my code**: click any line to see what it does, plus an automatic bug review.

One file (`index.html`), no install, works offline once loaded. Edits are saved in your browser.

## Put it on GitHub Pages

1. On github.com: **New repository** → name it `biobuzz-sim` → **Public** → **Create repository**.
2. **uploading an existing file** → drag in `index.html`, `README.md` and `.nojekyll` → **Commit changes**.
3. **Settings → Pages** → Source **Deploy from a branch**, Branch **main**, folder **/ (root)** → **Save**.
4. In about a minute it's live at `https://YOUR-USERNAME.github.io/biobuzz-sim/`.

To update, upload the new `index.html` to the same repo.

## At school

If `github.io` is blocked, open `index.html` straight from Google Drive or a USB stick. It works the same way.

## Controls

Click the field first. Left stick **W A S D**, right stick **arrow keys**, A B X Y **K L J I**, bumpers **Q E**, triggers **Z C**,
dpad **T F G H**, human player enters NECTAR **N**. A real gamepad works too.

With *Biobuzz TeleOp*: W/S drive, ←/→ turn, C intake, Z spit out, L flywheel on/off, hold K to shoot, T/G hood angle, F/H flywheel speed.

Note: the manual doesn't say how much weight tips a HIVE, so the sim uses an adjustable value (default 8, POLLEN = 1, NECTAR = 2).
The simulator understands the Java that FTC code usually uses; always build in Android Studio before trusting code on the real robot.
