# Pool Cam

Real pool, called like a sports video game. A camera above your table, the Pool Cam app on your TV, and your phone as the controller.

## Get the TV app

**Download:** [poolcam.apk](https://github.com/pbobdelux/pool-cam-downloads/raw/main/poolcam.apk) (version 0.5.0, build 554)

In the **Downloader** app on your TV, type this link (all lowercase):

`raw.githubusercontent.com/pbobdelux/pool-cam-downloads/main/poolcam.apk`

If that ever fails, this is the same file: `github.com/pbobdelux/pool-cam-downloads/raw/main/poolcam.apk`

### On a Google TV (TCL, Sony, Hisense, Chromecast with Google TV)

1. **Turn on developer mode:** Settings → System → About → click **Android TV OS build** 7 times.
2. **Get Downloader:** install the free **Downloader** app from the Play Store, and allow it to install apps when it asks.
3. **Install Pool Cam:** type the link above in Downloader. Pool Cam appears on your home screen.
4. **If Play Protect stops it:** choose **More details → Install anyway** (some TVs say **Install without scanning**).

Set Settings → System → Power & energy → Turn off display to **Never**, so the TV stays awake for the whole night.

### On a Fire TV

Works on Fire OS 7 and 8 (Settings → My Fire TV → About). It does not work on Fire OS 5 or 6, or on Vega OS sticks.

1. **Get Downloader:** search for **Downloader** on the home screen and install it.
2. **Allow it to install apps:** Settings → My Fire TV → Developer Options → Install unknown apps → **Downloader: On**. (No Developer Options? Settings → My Fire TV → About → click the device name 7 times.)
3. **Install Pool Cam:** type the link above in Downloader.

## Set it up once

1. **Open Pool Cam on the TV.** It shows the Pool Cam logo, one big code and **Connect to the TV using the Pool Cam app**.
2. **Scan it with your phone.** Use the Pool Cam iPhone or iPad app, or just your phone's camera. Your phone takes over from here; there is nothing to type on the TV.
3. **Link the camera** (a Tapo C120). In the Tapo app first, one time:
   - Camera → ⚙ Settings → Advanced Settings → **Camera Account**: make a username and password. **Capital letters count:** type them in Pool Cam exactly as the Tapo app shows them.
   - Me → Tapo Lab → **Third-Party Compatibility: On**.
4. **Check the table on your phone.** If the six dots sit on the pockets, tap **Looks right**. If not, tap **Fix them**, tap the six pockets on the picture and save.
5. **You're on the main menu:** Quick game, Tournament, Players.

That's it, for good. The TV keeps your table and your camera through restarts and updates, and comes back by itself when the camera or the Wi-Fi drops.

## Playing

- **Guests scan the TV's code** and land on the main menu, ready to play. They never see the camera or the table setup.
- **More phones can join** by scanning the same code.
- **Back always works**, and you can end a game or quit a tournament at any time.
- **Live voice (optional):** with your ElevenLabs key, the announcers say players' names and scores live. Enter it from the Pool Cam iPhone or iPad app, or from the phone that set up the camera: **Settings › Live voice**.
- **Sound:** on the TV, **Options › Sound** has **On**, **Calls only** and **Off**. The TV's tuning lives under **Options › Advanced**.

## New in build 554

- **The TV's code screen is just the logo, the code and one line:** "Connect to the TV using the Pool Cam app". It's up from the moment the camera connects, with nothing drawn over it.
- **Connect TV, top right**, on the phone page and in the iPhone/iPad app: a red dot means no TV, green means connected. One tap opens the scanner. The app also has a **Cast** button beside it, and nothing pops up about connecting unless you tap one.
- **The sound effects are real now**, all but one.
- **The referee speaks his review**, and the announcer lines that kept failing their recording check are voiced.

From build 537:

- **The winner card shows the real score.** It used to read 0-0.
- **"Quick game" has one name everywhere**, and New night says what it does: "Clear tonight's results and start fresh".
- **On the phone**, messages never cover a button, and the table's picture is as wide as the screen.
- **The number clips are in**, in Skye's voice so far.

## Still to come

- Music: every music cue is still a quiet placeholder.
- Names the announcers don't know yet: the next build makes them on the TV (with your ElevenLabs key) and carries more names and initials like AJ and TJ.
- The code works on the TV's own Wi-Fi only.

## No Pool Cam TV app?

The Pool Cam iPhone/iPad app can show the game on any TV: AirPlay, Chromecast or an HDMI adapter. Get it on TestFlight.

## About this build

This is a test build, signed with a test key, so each new build installs over the last one and keeps your setup. [BUILD.txt](BUILD.txt) says exactly which build this is. Store versions on Google Play and the Amazon Appstore come later.
