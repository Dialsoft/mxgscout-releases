# MXG Scout - What's new

## 2.1.1 - November 7, 2026
- **Live Cameras** now shows each camera's **serial number** (the `10_xx_yy_zz` the camera reports, which is also the name of its recordings folder) next to its network address, so you can match a live camera to its recorded clips at a glance.

## 2.1.0 - November 7, 2026
- **NEW: Live Cameras.** On the **Cameras** tab, click **Live Cameras**. Type your camera login at the top, click **Scan Network**, and MXG Scout sweeps your network for MOBOTIX cameras (the ones whose MAC starts with `00:03:C5`) and lists them in a tree on the left, grouped by name.
- Click any camera in the tree and it plays **live on the right**. The live picture is pulled straight from the camera as plain snapshots several times a second - no video engine, so it starts instantly and keeps working even on cameras the old live view couldn't handle.
- Tick **Remember login** and your camera password is saved encrypted on this PC (Windows DPAPI), so you don't have to type it next time.

## 2.0.0 - November 7, 2026
- **Brand-new ribbon interface.** The buttons are now organised into clear tabs across the top - **Home**, **Convert**, **Cameras** and **Help** - each holding only the tools for that job, grouped and labelled. The old crowded rows of buttons are gone.
- **Home** has your files and the Camera Grid. **Convert** has every MP4 setting in one place. **Cameras** has Find Cameras and the folder survey. **Help** gathers the tutorial, keyboard shortcuts, what's-new and updates.
- The **play controls** - timeline, play, rewind, frame step, speed, trim marks, snapshot, full screen and sound - stay along the bottom at all times, so they're always to hand whichever tab you're on.

## 1.9.1 - November 7, 2026
- Find Cameras has a **Save Camera Details** button: click one camera, then this, and MXG Scout saves a text file of that camera's technical replies (model, name, live-stream details) to your Desktop. It holds no password. Sending it to Dialsoft lets MXG Scout read your exact camera model and fine-tune live video.
- To fill in camera names in the list, type the Recordings folder (for example `Z:`) before scanning.

## 1.9.0 - November 7, 2026
- **NEW: live view.** After you run Find Cameras with "Remember login" ticked, the Camera Grid can show your cameras live - use the **Go Live** button on the grid toolbar, or right-click a camera and choose **Watch Live**. Click again to go back to the recordings. A red LIVE badge shows which tiles are live.
- Your camera login can be remembered on this PC, encrypted with Windows (DPAPI) so only your account on this computer can read it. Untick "Remember login" to forget it.

## 1.8.0 - November 7, 2026
- **Much faster Camera Grid.** Scrubbing is now instant: dragging the timeline shows each minute's picture straight away instead of waiting for the video engine.
- **New Rewind and Fast-forward buttons** on every camera - skim backwards or forwards through the recordings, a quick picture per minute, at 1x to 16x. Perfect for finding an event fast. Click again to stop; Play still gives full-motion video.

## 1.7.0 - November 7, 2026
- **NEW: a camera list** down the left of the Camera Grid, grouped by location (worked out from each camera's name - 53-TSU-CORP-ENTRANCE and 118-TSU-CORP-EXIT both sit under TSU-CORP). Tick or untick a camera, or a whole group, to show or hide it in the grid. Double-click a camera to make it big.
- The **List** button on the toolbar shows or hides the panel. Your choices are remembered.

## 1.6.1 - November 7, 2026
- Find Cameras now shows each camera's real name, and has a **Recordings folder** box so it can show names and mark which cameras have recordings even when you run it from a different PC than the one with the recordings drive.
- Fixed the camera Name/Model column, which could show stray text from the camera's web page.

## 1.6.0 - November 6, 2026
- **NEW: Find Cameras** (button in the Camera Grid, and under Help). It looks over your network, lists every MOBOTIX camera with its IP and MAC address, and checks your admin login on each one - green for OK, red for wrong password. It tries your login once per camera and never changes anything. Run it on a PC on the camera network.
- Each camera is matched to its recording folder by MAC address, and the list can be saved as a report. Your login is used only during the scan and is never saved to disk.

## 1.5.0 - November 6, 2026
- **NEW: Camera Grid** (button at the top). Point it at the folder where your MOBOTIX cameras save their recordings and see every camera at once, labeled with its real name and address. Each camera has its own play/pause, previous/next minute, speed (1x to 16x) and a timeline covering all of its recordings.
- Right-click a camera to go to a date & time, show that same moment on every camera, or open 1, 5 or 15 minutes in the main player (sound, frame-by-frame, MP4 for YouTube). Clips are saved in Videos\MXG Scout Clips.
- Double-click a camera to show it big with full detail; double-click again (or Esc) to go back. **Cameras** picks which ones are shown, **Per row** sets the layout. Everything is remembered.
- Times come from when the recording server saved each minute, so cameras with a wrong clock still line up.

## 1.4.5 - November 6, 2026
- Folder Survey: after you choose the recordings folder, the window **lists the folders inside it with tick boxes**, usually one per camera, shown with its IP address (`10_12_159_163` = camera 10.12.159.163) and when it last changed. Tick the camera(s) you want and only those are surveyed. Tick All / Untick All buttons included; nothing ticked = everything.

## 1.4.4 - November 6, 2026
- Folder Survey now shows a **progress window**: a percent-done bar, the folder it's reading, how many files and folders so far, time elapsed and roughly how long is left. A **Stop & Save Report** button (or Esc) ends it early and still saves the report.
- Tip: to survey just one camera, choose that camera's folder (for example `Y:\10_12_159_163`) instead of the whole drive.

## 1.4.3 - November 6, 2026
- Folder Survey is now a **Quick survey** by default: it visits every camera folder but opens only a few sample folders inside each one, so even a huge network archive finishes in a minute or two. Tick **Full survey** in the survey window to open every folder instead.
- Fixed: stopping a survey early with Esc skipped the look inside the sample files. It now always includes them.
- Folders are now visited in name order, so the report shows the oldest and newest recordings for each camera.

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
