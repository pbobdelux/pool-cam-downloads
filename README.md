# Pool Cam downloads

## Google TV / Android TV / Fire TV app (test build)

**Download:** [poolcam.apk](https://github.com/pbobdelux/pool-cam-downloads/raw/main/poolcam.apk)

- **Downloader code:** coming soon. Then you'll type a few digits in Downloader instead of the link.
- **Until then, type this link** (all lowercase): `raw.githubusercontent.com/pbobdelux/pool-cam-downloads/main/poolcam.apk`
- If that ever fails, this one is the same file: `github.com/pbobdelux/pool-cam-downloads/raw/main/poolcam.apk`
- `PoolCam-TV.apk` is the same file under its old name, so links you already have keep working.
- [BUILD.txt](BUILD.txt) says exactly which build this is: the commit, the date, the APK's SHA-256 and the signing certificate's.

### Install on a Google TV (TCL, Sony, Hisense, Chromecast with Google TV)

1. **Turn on developer mode:** Settings → System → About → click **Android TV OS build** 7 times.
2. **Get Downloader:** install the free **Downloader** app from the Play Store. When it asks, allow it to install apps.
3. **Install Pool Cam:** in Downloader, type the link above. Pool Cam installs and appears on your home screen.
4. **If Play Protect stops it:** it warns about any app that isn't from the Play Store. Choose **More details → Install anyway** (some TVs say **Install without scanning**).

**Keep the TV awake for the whole night.** A Google TV turns its screen off after a while even when an app is open. Set Settings → System → Power & energy → Turn off display: **Never**. If your TV also has its own sleep timer or auto-standby, turn that off too.

### Install on a Fire TV

**Which Fire TVs work:** the ones on Fire OS 7 or Fire OS 8. Check under Settings → My Fire TV → About: the software version starts with Fire OS 7 or 8. That covers, for example, the Fire TV Stick (3rd gen), Fire TV Stick Lite, Fire TV Stick 4K Max, the 2023 Fire TV Stick 4K and 4K Max, Fire TV Cube (2nd and 3rd gen) and Fire TV Omni and 4-Series TVs.

**Which don't:** older sticks on Fire OS 5 or 6, and Fire TVs on Vega OS (like the Fire TV Stick 4K Select), which can't install apps from outside Amazon's store.

1. **Get Downloader:** search for **Downloader** on the Fire TV home screen and install it (free, by AFTVnews).
2. **Allow it to install apps:** Settings → My Fire TV → Developer Options → Install unknown apps → **Downloader: On**. (No Developer Options? Settings → My Fire TV → About → click the device name 7 times.)
3. **Install Pool Cam:** in Downloader, type the link above. Pool Cam shows up under Your Apps & Channels.

### First run

1. **In the Tapo app first** (one time):
   - Tap your camera → ⚙ Settings → Advanced Settings → **Camera Account**, and make a username and password. This isn't your Tapo app login. When your phone offers to save it, say yes.
   - **Capital letters count.** Check the username on that screen letter by letter: the Tapo app or your phone's keyboard often turns the first letter into a capital ("Preston" instead of "preston"). Type it in Pool Cam exactly as the Tapo app shows it.
   - Me → Tapo Lab (or Third-Party Services) → **Third-Party Compatibility: On**. Without it the camera won't share its video.
2. The TV shows a QR code. Scan it with your phone's camera, or set it up from the Pool Cam iPad/iPhone app, which finds the TV by itself, asks for the 6-digit code on the TV's screen (so only someone in the room can set it up) and offers your saved camera login with one tap.
3. Enter only the Camera Account username and password, **with the same capital letters** as in the Tapo app. Your phone's password manager (Google or iCloud) can fill it in, and offers to save it once the camera accepts it. The TV finds the camera on your Wi-Fi by itself.
4. The TV tries the login on the camera right away and tells you exactly what to fix if something's off. Then it shows your table live, and your phone says **Connected ✓**.

After that the TV looks after itself:

- If the camera reboots or the Wi-Fi drops, the picture comes back by itself.
- If the camera gets a new address, the TV finds it. If it finds a camera with your login somewhere new, it asks **Is this your table?** before switching.
- On Google TV the camera login is also backed up to your Google account, so reinstalling Pool Cam (or a new Google TV) picks it up without asking.

### New in this build (0.5.0 build 498, Nov 12)

- **Set up the game on your phone.** The TV no longer asks you to type anything. It shows **Set up tonight's game on your phone** with one big QR; a phone or iPad that's already connected is named there instead, with no QR. Games, tournaments and players are all set up on the phone or iPad.
- **The announcers are in.** The recorded starter set: about 270 lines, the 100 most common names and 60 nicknames. These are first-pass voices, read plainly; the new cast, performed, comes in the next build.
- **Live voice (optional).** With your ElevenLabs key, the announcers say players' names and scores live. On your phone: scan the TV's QR, then **Settings › Live voice › Enter the ElevenLabs key**. Turn it off or on at the TV under **Options › Broadcast**. Every live line is saved on the TV, so it is made once.
- **Back always works.** Back on any show screen goes to the live table, and the screen says so. The menu has **End the night**, and an empty night ends by itself after 10 minutes.
- **The table locks on a slow TV.** It used to need three matching looks inside 2 seconds, which a slow TV could miss for ever.
- **The iPad keeps every pot** when the camera's picture arrives in bursts.

From build 482:

- **Real sound effects.** 83 of the show's 141 sounds are now the real ones (ball clacks, pockets, the crowd). The rest are still quiet placeholders.
- **No more odd background noise.** A sound that isn't finished yet now plays as silence. **Options › Sound** has **On**, **Calls only** and **Off**.
- **After you adjust the pockets, the TV goes back to the menu** and says **Table saved ✓**. It no longer jumps into tournament night.

From build 474:

- **The ball dots stay on the table.** They show only over the live picture, never over the show's own screens.
- **A game keeps the table.** While a game you started from a phone or the iPad is on, the TV won't offer to start the night; starting one asks "End this game and start the night?" first.
- **The table locks on by itself.** Once the picture is up, the TV finds the 6 pockets: "Finding the table…", then blue rings close on the pockets and **TABLE LOCKED**. No button. It follows the table if the camera sways and finds it again if it's lost.
- **Setup in clear steps** on the TV and the phone: connect your phone, sign in to the camera, find the camera, lock onto the table, ready. **Capital letters count** in the camera's username; if the first letter's case is off, Pool Cam tries it the other way and tells you.
- **Back never traps you.** Every menu closes one step with Back, and leaving Pool Cam asks first.
- **Adding a player is just a name.** The nickname is optional, under **Add a nickname**.
- **Disconnect camera** is in Options › Camera, and **Camera's back ✓** shows when the picture returns after a drop.

Earlier in this build:

- **The SIXPOCKET SPORTS show on screen.** The draw, the bracket, NOW CALLING, the champion and LAST CALL. When nothing's on, the showreel plays.
- **WELCOME BACK.** If the TV restarts mid-night, the night picks up where it was, with the score.
- **Phones and the iPad keep score,** add players' photos, and get the night's results to take home.
- **Quicker calls (0.5.0 build 456).** The TV now watches the table at a true 10 frames a second (it was 7.5), its ball tracking does about 40% less work a frame, and each pot goes straight to the night, so the calls come sooner after a ball drops.
- **The camera's picture arrives.** "Find my table" no longer gives up while the camera's picture is still starting, and the camera login is saved before your phone says **Connected ✓**, so a restart keeps it.
- **Game mode by itself.** Pool Cam asks the TV for its low-latency picture mode. Options › Details says **TV game mode: asked for**. If it says your TV doesn't have one, set the TV's picture mode to **Game** yourself.
- **How far behind it is.** Options › Details shows how far behind live the tracking and the picture are.
- **For the quickest picture and calls:** keep the iPad plugged in with Pool Cam open, so it does the ball tracking.

### Ball tracking (new)

The TV now follows every ball itself, with no computer.

1. Keep the whole table in the picture with the light on. The TV finds the 6 pockets by itself and shows **TABLE LOCKED**.
2. To check it: hold OK for the menu, then **Options › My table**. The blue circles should sit on the pockets.
3. If one doesn't, press **Adjust**: the arrows move a pocket, OK goes to the next, and it saves after the sixth.

The menu also has **Dots** (show the balls on screen) and **Track** (turn tracking on or off). **Light** uses the camera's smaller stream if the TV is slow; the health line in the menu shows the frames per second. Tracking opens a second video connection to the camera. If your camera refuses it, the menu will say so.

### No Pool Cam TV app? Use the iPad or iPhone app

The Pool Cam app shows the camera, the score and the shot calls on any TV: **AirPlay** to Apple TV and most Samsung, LG, Vizio, Sony and Roku TVs (Screen Mirroring), **Cast** to a Chromecast or a TV with Chromecast built in (about 2 seconds behind, with the show's sound on the TV from TestFlight build 19), or an **HDMI adapter**. Get it on TestFlight.

### About this build

This is a test build, signed with a test key, so each new test build installs over the last one. Pool Cam will soon switch to its own private key. When it does, this page will say so, and you'll uninstall Pool Cam once, install the new one and type the camera login once more. After that, updates install over it again. Store versions on Google Play and the Amazon Appstore come later.
