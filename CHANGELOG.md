# MXG Scout - What's new

## 1.4.2 - November 6, 2026
- **Rebuilt the Folder Survey window.** Everything is in one window: type or paste a folder, click a drive (mapped network drives included), use Browse… for the normal Windows folder picker, or drag a folder in from File Explorer.
- Fixed: the survey window could close by itself while you were typing a path.
- The last folder you surveyed is remembered, and a mistyped or unreachable folder now shows a clear message instead of closing the window.
- The finished report opens in an easy-to-read fixed-width view.

## 1.4.1 - November 6, 2026
- The Folder Survey now has its **own folder chooser that lists every drive, including mapped network drives** (the old Windows box could hide them). You can also type or paste a path like `\\NAS\Mobotix`, or use Browse….
- If MXG Scout is running as administrator, Windows hides mapped drive letters; they are now shown by their network path instead, and typed drive letters are switched to the network path automatically.

## 1.4.0 - November 6, 2026
- **New: Help → Survey a MOBOTIX Recording Folder.** Point it at the folder (or network share) where your cameras save their recordings and it writes a text report on your Desktop describing how the folders and files are laid out. It only reads (nothing is changed), and no pictures or sound go into the report.
- Send the report to Dialsoft so a future version can show all your cameras in one grid with shared playback controls.
- Press **Esc** to stop a survey early; the report still covers what was looked at.

## 1.3.0 - November 6, 2026
- **Built-in Getting Started tutorial**: a short guided tour that points at each control. It starts by itself the first time, and any time from Help → Getting Started Tutorial.
- **Explainer video**: Help → Watch the Explainer Video (also on [dialsoft.com](https://dialsoft.com/#mxgscout)).
- Bigger, labeled **Volume** slider next to the Sound box in the player controls.
- Help menu now has a proper **About MXG Scout** and a separate **Keyboard Shortcuts** list.

## 1.2.0 - November 5, 2026
- **Sound!** The camera's microphone sound now plays while you watch, in sync with the picture, including after scrubbing, pausing and the skipped dead gaps.
- "Sound" on/off box (key: **M**) and a volume slider that can also make quiet camera microphones louder (up to double). Both take effect immediately and are remembered.
- Sound plays at normal 1× speed and is muted at other speeds.

## 1.1.0 - November 5, 2026
- **Automatic updates.** MXG Scout checks for a new version when it starts and every 6 hours. A yellow bar offers "Update now". The download is verified (exact size, SHA-256 checksum and version check), then MXG Scout swaps itself in and restarts with the same files in its list.
- "Check for updates automatically" setting (takes effect immediately).
- The title bar shows whether you're up to date.
- New Help menu: Release Notes, Check for Updates Now, Keyboard Shortcuts & About.
- After an update, MXG Scout shows what's new automatically.
- Smaller download (about 39 MB instead of 105 MB). The built-in video engine is now stored compressed and unpacked on first run.

## 1.0.0 - November 5, 2026
- First release. Opens MOBOTIX .MXG camera recordings. Drag and drop files or whole folders.
- Instant, frame-exact timeline scrubbing: the file is scanned once, then any spot appears in a fraction of a second.
- Play / pause, frame-by-frame forward and back, jump 10 seconds, speeds from 0.25× to 16×, full screen.
- Shows the camera's real recording date and time for every picture.
- Skips the camera's dead gaps during playback.
- Converts to YouTube-ready MP4 (H.264 + AAC), one file or a whole batch, with sound.
- Trim with Mark In / Mark Out. Full-resolution PNG snapshots.
