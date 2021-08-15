# Hycon OS Source Changelog.


## V4.5 | ELEGANT (15-08-2021)

• Merged August AOSP Security Patch

• Update PixelPropsUtil to August FP

• Added Preferred Refresh Rate 

• Added Toggle for QS Media Player background with artwork

• Added Reboot Tile

• Added new Font Engine from CorvusOS

• Added Numerous amount of Fonts styles

• Added dynamic VoLTE & VoWiFi icons

• Added VoLTE/VoWIFI icons from Vivo X60 Pro

• Added Brightness Sliders

• Added optional OOS QS Clock

• Added support fonts from Substratum theme packages

• Added button to upload crash information to katbin

• Added Machine Learning Gestures

• Updated Default Wallpaper

• Improve FPS Info output formatting and performance

• Update Now Playing database as of August 4, 2021

• Removed dead code from Telephony which uses wakelock

• Grant MediaProvider access to /mnt/media_rw & /mnt/pass_through

• VibratorService: update constant values for OnePlus HAL

• Added new ShapeshitOS lockscreen clock

• Fixed lag while expanding qs

• Miscellaneous improvements


## V4.0 | EPHEMERAL(11-07-2021)

• Merged July Security bulletin resolutions.

• Added Edge Music Control Gesture.

• Added ShapeShift Volume Panel Style.

• Added P404 Volume Panel.

•Added Android S & S(dp3) lockscreen Clocks.

• Android S clocks will change colours according to lockscreen wallpaper.

• Added Android S style switches.

• Added Gaming mode.

• Added Gaming mode tile.

• Added Heads-up Blacklist & Stoplist options in hub.

• Added less boring Heads-up option.

• Fixed NPE when notification icon is empty.

• Added support for MiSound FX.

• Added support for DiracSound FX.

• fixed Default min refresh rate to 60 Hz.

• Added Alarms Blocker under developer settings.

• Added Wakelock Blocker under developer settings.

• Added one minute timeout to global actions dialog

• Added clipboard toast toggle under privacy settings.

• Added back QS data usage.

• Added Adaptive Playback feature under developer settings.

• Allowed changing face unlock method when locked

• Added lockscreen background blur.

• Spoofed devices to Pixel XL for Google Photos unlimited upload storage.

• Removed duplicated lock icon entries from HyconHub.

• Fixed wallpaper crash on homescreen.

• Updated default lock and unlock sounds.

• Updated default wallpaper.

• Fixed old bootanimation script issues.

• Removed QS scrim and transparency.

• Updated Exfat repos and fixed its known issues.

• Added Permissions Hub under privacy settings

• Fixed high battery drain after using flashlight.

• Fixed some OTA Updater issues.

• Reverted redesigned mediaplayerview to fix QS issues.

• Avoided double ripple in QS detail view.

• Made iOS clipboard text optional.

• Prevented guest user from toggling mobile data from Quick Setting.

• Fixed QS detail panel with header image enabled.

• Allowed users to block individual Audio apps from resuming in expanded QS.

• Used Material icons for missed calls.

• Tried to fix upstream status bar+keyguard bug.

• Added some Faceunlock and AppLock improvements.

## v3.5 | SUNRISE (17-06-2021)
• June Security bulletin resolution have been merged.

• Fixed 15 second auto-lock timer for AppLock , when app is stopped while moving to recents.

• Added MIUI volume style plugin.

• Added Compass tile.

• Added Screen Off FOD.

• Added Option to set transparency of Quick settings panel.

• Added Option for theming QS with wallpaper colors.

• Added Option for theming QS with Custom colors too.

• Added Toggle for iOS-like toast notification for clipboard access.

• Replaced default Aosp Blur with Glass blur.

• Updated HyconOS logo in about settings page.

• Updated default wallpaper.

• Added support for one shot auto-brightness.

• Added DescendantSeamlessClockSwitch.

• Added Fluid lock clock V2.

• Improved face unlock detection.

• Addd rounded corners to activity open/close animation.

• PixelPropsUtils are Update to June 2021 fingerprint.

• Added reticker feature.

• Added iOS-like toast notification for clipboard access.

• fixed broadcast receivers overflow for system_server.

• Updated default sounds for ringtone and notification.

• Enabled AiAi content suggestions service.

• Added APN configs for LIDL Connect , TPG Singapore,  AT&T 310-280 ids.

• Added lots of new wallpapers in Hycon walls app.

• Updated HyconOS Bootanimation.

## v3.0 | AURORA (18-05-2021)

CHANGELOG:-
- May Security bulletin resolution have been merged.
- allowed to set back swipe deadzone in gestures.
- Added screeenshot quality setting.
- Updated Hycon OS Logo in About Phone section.
- Added sound tile into Quick Settings.
- Added Google Sound Search Tile In Quick Settings.
- Added Mono/stereo audio tile (headphone in one ear).
- Added Heart icon shape of QS tiles.
- Allowed scheduling always on display.
- Added support for mixed time and sun time modes.
- Added Account for disabled  doze.
- Added Show and edit Ambient Icons on Lockscreen.
- Added option to enable AOD on charging only.
- Added Lockscreen & ambient Pulse.
- Added Navbar Pulse.
- Added Ambient Notification bars.
- Added Edge Lighting feature.
- Added duration and count for ambient notification pulse.
- Added colored Statusbar Notification Icons Feature.
- Made colored Statusbar Notification Icons optional.
- Added colored Notification  Headers Feature.
- Made colored Notification  Headers Feature optional.
- Added Option to Change duration and repeat counts of ambient edge.
- Added Support for Double tap to trigger doze.
- Enabled payphone call blocking option.
- Package installer will show current and new version on app installation.
- Toasts will Show app icon on system text as well.
- Added Octavi's lockscreen clock.
- Allowed media art with enabled facelock lockscreen to bypass.
- Allowed selected camera apps to skip unconfigure.
- Defined blur radius in. device-independent pixels.
- Bump background blur radius to 155px.
- Removed background tint from emergency tile.
- Imported TensorFlow Lite model.
- Fixed Notch Hide Overlays.
- Redesigned Media Player View.
- Added option to disable refresh rate lowering in battery saver.
- updated positioning of analog clock on lockscreen.
- Removed side padding from the dialog Of packageInstaller.
- Improved notification/headsup group header layouts.
- Added New Wallpapers To HyconWalls.

## v2.5 | HASHIRA (16-04-2021)

CHANGELOG:-

- Added option to set QS panel columns and rows.
- Introduced automated DC Dimming.
- Added FOD icon picker in HyconHUB.
- Added HyconOS fod icon in FOD picker.
- Allowed additional padding on left side of heads up notifications. 
- Added Shapeshift lockscreen clock.
- Added Lock icons improvements for face unlock.
- Disabled camera shutter sound in all countries.
- Added Bluetooth and wifi timeout feature.
- Disabled full screen keyboard.
- Improved HyconHub Layout.
- Added Demon Slayer ringtone and notification sound.
- Changed Hycon logo in About phone and 
- Added Rengoku Kyojuro's logo.
- changed default wallpaper.
- Added Hycon Wallpapers app .
- Added option for statusbar brightness  control.
- imported new gboard overlay.
- Fixed Volume panel not following rounded corners partially.
- Fixed AOD flickers on some devices.
- Fixed bug on high contrast text
- Fixed black screen after doze.
- Volume panel plugins can be on left side now :)
- more under the hood improvements to make rom smooth.

## v2.0 | Blizzard (28-03-2021)

Changelog :-

# Add-ons And Updates :
- Merged March security patch.
- Implement Gvisual mod.
- Add Fluid lockscreen clock.
- Add Tux lockscreen clock
- Add 404 IDE lockscreen clock.
- Added systemwide Applock With face unlock support.
- Added new face lock implementation.
- Added Oneplus file manager.
- Added option to hide gesture navbar.
- allow customizing gesture navbar.
- Added alert slider support.
- Alert slider notifications for supported devices.
- Added more apps to pixelprop utils .
- Removed divider between QS tiles and media player.
- add/remove QS tiles with one click.
- Added Dual Channel into Bluetooth Audio. Channel Mode developer options.
- Set all devices model to Pixel 3 XL for Google.
- Added Russian Language translation into HyconHub.
- Updated HyconHub logo in settings dashboard.
- Added support for battery Moto Mods.
- Updated OOS Volte & Vowifi icons.
- implemented OnePlus proprietary vibrator format.
- Improved Fod stuff.
- Disabled blur wakeup animation.
- Implemented phone ringtone setting for Multi SIM device.
- Disabled rotation on lockscreen.
- Added Vooc , Warp & Dash Charging Support.
- Allowed to limit the max framerate of built-in screen recorder.
- Implemented Hycon Os Updater. You guys can enjoy OTA support now .

# Fixed bugs & killed demons :
- Fixed Lockscreen Carrier Text Padding
- Fixed "Clear All" recent app screen loop bug
- Fixed Lockscreen Carrier Text Padding
- Fixed inactive state Wifi Icon in Kai Icon Pack.
- Fixed background colouring for settings themed icons.

## v1.5 | Zephyrus (15-02-2021)
Changelog :- 
# Additions & Implementations
- Revamped settings dashboard icons for all categories.
- Added lottie animations.
- Moved theming stuff to Hub.
- Added Fastcharge preference to Battery settings.
- Settings: QR Scanner pass proper frame Width and Height .
- Unlock mobile network settings when airplane mode is on.
- Tint data usage bar with activated control color.
- Remove roaming warning, app uninstall, disable confirmation dialogs.
- Added drawable for private DNS.
- Avoided enforcing weird backgrounds in Settings.
- Better spaced searchbar in dashboard.
- Added avatar icon in SearchBar.
- Redesigned searchbar header.
- Added Initial bootleg gradient color.
- Added FPS and CPU info overlay and tile.
- Added long screenshot support.
- Add delete action chip for screenshot.
- Introduce QS tile style picker .
- Limit resolution to 4k for 32 bit processes.
- Implement POSP Volume Plugin Manager.
- Added Disco Dingo tiles mode .
- Added QS header With custom header image offset.
- Added option to Allow limiting maxc framerate of built in screen recorder.

# Killed Bugs and Fixed demons
- Fixed Screen drag for swipe to screenshot
- Updated divider color in dark theme.
- Fixed inconsistent USB preference screen title.
- Fixed stray divider in connected devices screen.
- Fixed default brightness 0 display level .
- Fixed FC in settings brightness.
- Fixed invalid private DNS help text if URI is missing.
- Fixed Hycon Hub Logo in Settings Dashboard.


## v1.0 | Aureus (01-02-2021)

- Added support for per app network isolation.
- Added Face Unlock support.
- Added option to Allow user to add/remove QS tile with one click.
- legacy apps can scale fully to the display's aspect ratio
- Added option to reset Battery stats.
- Added caffeine qs tile.
- Added DataSwitchTile.
- Added Sync QS Tile.
- Enabled fingerprint swipe gesDismiss notifications with back FP left/right swipe.
- Added three-fingers-swipe to screenshotscreenshot.
- Added lockcreen charging info.
- added Double tap to sleep on statusbar
- Added Smart Charging.
- Added capability to allow tethering to use VPN upstreams.
- Added Network traffic indicator.
- Added Volume Rocker Wake.
- Added volume key music control.
- Added option to use 4G icon instead LTE.
- Added Option to Display Data Disabled Indicator Icon.
- Revamped settings dashboard, Thanks To WaveOS For it.
- Added New Battery Meterview Thanks to FluidOS of it.
- Added option for choosing a custom vibration pattern.
- Added Advanced Reboot option.
- Moved blur toggle under Display options.
- Added battery health.
- Added VoLTE and VoWiFi icons.
- Add vibration patterns from OOS.
- Added Support for In-Call Vibration options.
- Toggle to Unlink Call and Notification volumes.
- Added Option to scramble PIN.
- Added option forSignature spoofing.
- Moved brightness slider at bottom and visible in qs.
- Switched to OOS 11 QS layout.
- Added Toggle for QS media player.
- Added Option to Hide Lock and Statusbar on Lockscreen.
- Added option for QS header data usage.
- Added Lockscreen media art.
- Added optionhide Notification headers.
- Added New Systemui Themes under Color Bucket.
- Added optional support to toggle new QS tint.
- Added OOS style switches.
- Added custom RGB accenter.
- Added Custom Clock faces.
- Added AOD and ambient display tiles.
- Added Material Toast notifications.
