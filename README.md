# Pool Cam downloads

## Google TV / Android TV / Fire TV app (test build)

**Download:** [PoolCam-TV.apk](https://github.com/pbobdelux/pool-cam-downloads/raw/main/PoolCam-TV.apk)

### Install on a Google TV (TCL, Sony, Hisense, Chromecast with Google TV)

1. **Turn on developer mode:** Settings → System → About → click **Android TV OS build** 7 times.
2. **Get Downloader:** install the free **Downloader** app from the Play Store. When it asks, allow it to install apps.
3. **Install Pool Cam:** in Downloader, type the download link above. Pool Cam installs and appears on your home screen.

### Install on a Fire TV (Fire TV Stick, Fire TV Cube, Fire TV Edition TVs)

1. **Get Downloader:** search for **Downloader** on the Fire TV home screen and install it (free, by AFTVnews).
2. **Allow it to install apps:** Settings → My Fire TV → Developer Options → Install unknown apps → **Downloader: On**. (No Developer Options? Settings → My Fire TV → About → click the device name 7 times.)
3. **Install Pool Cam:** in Downloader, type the download link above. Pool Cam shows up under Your Apps & Channels.

### First run

1. **In the Tapo app first** (one time):
   - Tap your camera → ⚙ Settings → Advanced Settings → **Camera Account**, and make a username and password. This isn't your Tapo app login. When your phone offers to save it, say yes.
   - Me → Tapo Lab (or Third-Party Services) → **Third-Party Compatibility: On**. Without it the camera won't share its video.
2. The TV shows a QR code. Scan it with your phone's camera, or set it up from the Pool Cam iPad/iPhone app, which finds the TV by itself and offers your saved camera login with one tap.
3. Enter only the Camera Account username and password. Your phone's password manager (Google or iCloud) can fill it in, and offers to save it once the camera accepts it. The TV finds the camera on your Wi-Fi by itself.
4. The TV tries the login on the camera right away and tells you exactly what to fix if something's off. Then it shows your table live, and your phone says **Connected ✓**.

After that the TV looks after itself:

- If the camera reboots or the Wi-Fi drops, the picture comes back by itself.
- If the camera gets a new address, the TV finds it. If it finds a camera with your login somewhere new, it asks **Is this your table?** before switching.
- On Google TV the camera login is also backed up to your Google account, so reinstalling Pool Cam (or a new Google TV) picks it up without asking.

### Ball tracking (new)

The TV now follows every ball itself, with no computer.

1. Press OK on the remote to open the menu, then choose **Find my table**.
2. Pick your table's size and press **Find**. Keep the whole table in the picture, with nobody leaning over it.
3. Check the yellow outline follows the inside edge of the cushions. Press **Looks right ✓**, or **Adjust** to move a corner with the arrow keys.

The menu also has **Dots** (show the balls on screen) and **Track** (turn tracking on or off). **Light** uses the camera's smaller stream if the TV is slow; the health line in the menu shows the frames per second. Tracking opens a second video connection to the camera. If your camera refuses it, the menu will say so.

### No Pool Cam TV app? Use the iPad or iPhone app

The Pool Cam app runs the whole show and puts it on any TV: **AirPlay** to Apple TV and most Samsung, LG, Vizio, Sony and Roku TVs (Screen Mirroring), **Cast** to a Chromecast or a TV with Chromecast built in, or an **HDMI adapter**. Get it on TestFlight.

This is a test build, signed with a test key, so updates install over it. Store versions on Google Play and the Amazon Appstore come later.
