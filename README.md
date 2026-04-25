# laptop-settings-windows-11

```plaintext
v1.20260422.3
```

Relevant as of `2026-04-15+0000`.
At a minimum should work with

```plaintext
Windows 11 Home 25H2 Build 26200.8037
```

## Purpose

I wrote these so I have a quick reference for the changes I've been applying everytime on a fresh Windows install. Walang command line or registry edits, all within user interfaces lang. There are some default settings that are already good as is from a fresh install so they do not have to be modified. 

## 1. Getting Started

### 1.1 Windows Settings

- press and hold `Windows key` then press `i`

> [!NOTE]
> Please follow and apply the settings below as exactly written.

## 2. Absolute Minimum

### 2.1 Privacy and security

`Privacy and security` -> `Device encryption`

- turn off `Device encryption`
- click `Turn off`

> [!NOTE]
> Turns off encryption and decryption of every file you open so it gives a small performance boost. We turn this off because it is an overkill security feature for a personal computer, if a Windows update glitches Windows up and triggers BitLocker lock and you don't have the BitLocker recovery key saved, this encryption can permanently lock you out of your own files.

> [!WARNING]
> Make sure to keep your laptop or computer turned on while it is decrypting your files, plug it in! You can still use it while it does that. Check its progress from time to time, completes the decryption much faster on SSDs.

`Privacy and security` -> `Device encryption` -> `BitLocker drive encryption` -> `Control Panel` -> `System and Security` -> `BitLocker Drive Encryption`

-> `Operating system drive`

- turn off `BitLocker` on every drive shown, if not already
- click `Turn off BitLocker`

-> `Fixed data drives`

- turn off `BitLocker` on every drive shown, if not already
- click `Turn off BitLocker`

> [!NOTE]
> Turns off encryption and decryption of every file you open so it gives a small performance boost. We turn this off because it is an overkill security feature for a personal computer, if a Windows update glitches Windows up and triggers BitLocker lock and you don't have the BitLocker recovery key saved, this encryption can permanently lock you out of your own files.

> [!WARNING]
> Make sure to keep your laptop or computer turned on while it is decrypting your files, plug it in! You can still use it while it does that. Check its progress from time to time, completes the decryption much faster on SSDs.

`Privacy and security` -> `Recall and snapshots`

- turn off `Save snapshots`

> [!NOTE]
> If it's there, turn it off.

### 2.2 Bluetooth and Devices

`Bluetooth and devices` -> `Mouse`

- set `Mouse pointer speed` to `10/20` (default)

> [!TIP]
> If you wanna change your mouse sensitivity, do it inside an app or game and using your mouse's software DPI settings, not the `Mouse pointer speed`.

- turn off `Enhance pointer precision`

> [!NOTE]
> Despite how it's named, we actually turn this off to get rid of mouse acceleration so that the movement of your cursor depends only on how far you move your mouse, not how fast you move it.

### 2.3 Accessibility

`Accessibility` -> `Keyboard` -> click `Sticky keys`, it's a dropdown

- turn off `Sticky keys` (default)
- turn off `Keyboard shortcut for Sticky keys`

> [!NOTE]
> Turn it off because it can cause accidental interruption when you press the `Shift` key quickly 5 times in a row anywhere. A regular user don't need it.

`Accessibility` -> `Keyboard` -> click `Filter keys`, it's a dropdown

- turn off `Filter keys` (default)
- turn off `Keyboard shortcut for Filter keys`

> [!NOTE]
> Turn it off because it can cause accidental interruption when you press and hold the right `Shift` key for 8 secs anywhere. A regular user don't need it.

`Accessibility` -> `Keyboard`

- turn off `Toggle keys` (default)

`Accessibility` -> `Narrator`

- turn off `Keyboard shortcut for Narrator`

`Accessibility` -> `Mouse`

- turn off `Hide pointer while typing`

`Accessibility` -> `Visual effects`

- turn on `Always show scrollbars`

### 2.4 Control Panel

1. press the `Windows` key
2. type `control panel`
3. find it and open it
4. at top-right, set `View by:` to `Category`

`Control Panel` -> `Hardware and Sound` -> `Power Options` -> `Choose what the power buttons do` -> `Change settings that are currently unavailable` -> `User Account Control`

- click `Yes` if prompted
- turn off `Turn on fast startup (recommended)`
- click `Save changes`

> [!NOTE]
> When `Turn on fast startup (recommended)` is turned on, Windows doesnt actually shut down, it hibernates saving stuff on memory so it launches back up faster the next time you turn it on, it can be problematic at times so we turn it off to prevent future headaches so your computer or laptop can start fresh and power cycle properly. Affects your boot times slightly, doesn't matter that much on SSDs, maybe 1-2 seconds.

### 2.5 Apps

`Apps` -> `Resume`

- turn off `Resume`

### 2.6 System

`System` -> `Display` -> `Scale and layout`

- set `Scale` to a scale that is marked as `(Recommended)`

- set `Display resolution` to a resolution that is marked as `(Recommended)`

`System` -> `Display` -> `Related settings` -> `Advanced display` -> `Display information`

- set `Choose a refresh rate` to the highest value when plugged in or to the lowest value when on battery
- turn off `Dynamic refresh rate`

> [!NOTE]
> We turn off `Dynamic refresh rate` to have the power consumption of the Display be more predictable. On laptops you shouldn't leave `Choose a refresh rate`'s value the way it is all the time when you're on battery, take extra care of your laptop's battery especially on gaming laptops lol.

`System` -> `Power and battery` -> click `Power Mode`, it's a dropdown

- set `Plugged in` to `Balanced` (default)
- set `On battery` to `Balanced`

`System` -> `Power and battery` -> `Screen, sleep, and hibernate timeouts`  -> `Plugged in`

- set `Turn my screen off after` to `Never`
- set `Make my device sleep after` to `Never`

`System` -> `Power and battery` -> `Screen, sleep, and hibernate timeouts`  -> `On battery`

- set `Turn my screen off after` to `Never`
- set `Make my device sleep after` to `Never`

`System` -> `Power and battery` -> `Lid, power and sleep button controls` -> `Plugged in`

- set `Pressing the power button will make my PC` to `Do nothing`
- set `Pressing the sleep button will make my PC` to `Sleep` (default)
- set `Closing the lid will make my PC` to `Sleep` (default)

> [!NOTE]
> Power button presses no longer shuts down to prevent accidental shut downs.

`System` -> `Power and battery` -> `Lid, power and sleep button controls` -> `On battery`

- set `Pressing the power button will make my PC` to `Do nothing`
- set `Pressing the sleep button will make my PC` to `Sleep` (default)
- set `Closing the lid will make my PC` to `Sleep` (default)

> [!NOTE]
> Power button presses no longer shuts down to prevent accidental shut downs.

`System` -> `Clipboard`

- turn on `Clipboard history`

`System` -> `Advanced` -> `Taskbar`

- turn on `End Task`

`System` -> `Advanced` -> `File Explorer` -> `File Explorer`

- turn on `Enable long paths`

`System` -> `Advanced` -> `File Explorer` -> `File Explorer` -> `File Explorer`

- turn on `Show file extensions`

`System` -> `Sound` -> `Output` -> click `Speakers`, it's a dropdown -> `Properties`

- set `Output settings` -> `Format` to `2 channels, 24 bit, 48000 Hz (Studio Quality)`
- turn off `Advanced settings` -> `Audio enhancements`
- turn off `Advanced settings` -> `Spatial sound`

`System` -> `Sound` -> `Output` -> click `Headphones`, it's a dropdown -> `Properties`

- set `Output settings` -> `Format` to `2 channels, 24 bit, 48000 Hz (Studio Quality)`
- turn off `Advanced settings` -> `Audio enhancements`
- turn off `Advanced settings` -> `Spatial sound`

> [!NOTE]
> `24 bit, 48000 Hz` is a good set-it-and-forget-it setting to have. Turn off `Audio enhancements` and `Spatial sound` because you don't need filters on sound. Clear stereo sound lang sa right and left channel and it's all good. If you had a game or other softwares that also handle their own sound, filters stack up on each other which is a nono, that's why it's better to have Windows' sound adjustments off.

`System` -> `Sound` -> `Input` -> click `Microphone`, it's a dropdown -> `Properties`

- set `Output settings` -> `Format` to `2 channels, 16 bit, 48000 Hz (DVD Quality)`
- turn off `Advanced settings` -> `Audio enhancements`

`System` -> `Sound` -> `Advanced` -> `More sound settings` -> `Sound` -> `Sound`

- turn off `Program Events:` -> `Play Windows Startup sound`
- click `OK`

`System` -> `About` -> `Related links` -> `Advanced system settings` -> `System Properties` -> `Advanced` -> `Startup and Recovery` -> `Settings...` -> `System failure`

- turn off `Automatically restart`
- click `OK`

> [!NOTE]
> We turn it off because when your computer encounters a BSOD (Blue Screen of Death), it doesn't restart your computer by itself after a certain time. It helps letting you know that a BSOD actually happened and the error that caused it. 

### 2.7 Bluetooth and devices

`Bluetooth and devices` -> `Touchpad` -> click `Touchpad`, it's a dropdown

- turn off `Leave touchpad on when a mouse is connected`

`Bluetooth and devices` -> `Keyboard` -> `Shortcuts and hotkeys`

- turn on `Use the Print screen key to open screen capture` (default)

## 3. A Little Deeper

### 3.1 Personalization

`Personalization` -> `Themes` -> `Related settings` -> `Desktop icon settings` -> `Desktop icons`

- turn on `Desktop icons` -> `Computer` (default)
- turn on `Desktop icons` -> `User's Files`
- turn on `Desktop icons` -> `Recycle Bin` (default)
- turn off `Allow themes to change desktop icons`

> [!NOTE]
> These are most often accessed to access more things, so it kinda makes sense to always have these on desktop.

### 3.2 Time and language

`Time and language` -> `Typing`

- turn off `Show text suggestions when typing on the physical keyboard`
- turn off `Multilingual text suggestions`
- turn off `Autocorrect misspelled words`
- turn off `Highlight misspelled words`

`Time and language` -> `Date and time`

- turn on `Set time automatically` (default)
- set `Time zone` to `(UTC+08:00) Kuala Lumpur, Singapore` (varies, this is for the Philippines)

### 3.3 Control Panel

1. press the `Windows` key
2. type `control panel`
3. find it and open it
4. at top-right, set `View by:` to `Category`

`Control Panel` -> `Hardware and Sound` -> `Power Options`

- set `Selected plan` to `Balanced`

`Control Panel` -> `Hardware and Sound` -> `Power Options` -> `Selected plan` -> `Balanced` -> `Change plan settings` -> `Change advanced power settings`

- set `Hard disk` -> `Turn off hard disk after` -> `On battery (Minutes)` to `0`
- set `Hard disk` -> `Turn off hard disk after` -> `Plugged in (Minutes)` to `0`
- set `Desktop background settings` -> `Slide show` -> `On battery` to `Available`
- set `Desktop background settings` -> `Slide show` -> `Plugged in` to `Available` (default)
- set `Wireless Adapter Settings` -> `Power Saving Mode` -> `On battery` to `Medium Power Saving`
- set `Wireless Adapter Settings` -> `Power Saving Mode` -> `Plugged in` to `Maximum Performance` (default)
- set `Internet Explorer mode` -> `JavaScript Timer Frequency` -> `On battery` to `Maximum Performance`
- set `Internet Explorer mode` -> `JavaScript Timer Frequency` -> `Plugged in` to `Maximum Performance`
- set `Intel(R) Graphics Settings` -> `Intel(R) Graphics Power Plan` -> `On battery` to `Balanced`
- set `Intel(R) Graphics Settings` -> `Intel(R) Graphics Power Plan` -> `Plugged in` to `Balanced`
- set `Sleep` -> `Allow wake timers` -> `On battery` to `Disable` (default, may be hidden)
- set `Sleep` -> `Allow wake timers` -> `Plugged in` to `Disable` (may be hidden)
- set `USB settings` -> `USB selective suspend setting` -> `On battery` to `Disabled`
- set `USB settings` -> `USB selective suspend setting` -> `Plugged in` to `Disabled`
- set `PCI Express` -> `Link State Power Management` -> `On battery` to `Off`
- set `PCI Express` -> `Link State Power Management` -> `Plugged in` to `Off`
- set `Processor power management` -> `Minimum processor state` -> `On battery` to `5` (default)
- set `Processor power management` -> `Minimum processor state` -> `Plugged in` to `5` (default)
- set `Processor power management` -> `Maximum processor state` -> `On battery` to `100` (default)
- set `Processor power management` -> `Maximum processor state` -> `Plugged in` to `100` (default)
- set `Processor power management` -> `System cooling policy` -> `On battery` to `Passive` (default)
- set `Processor power management` -> `System cooling policy` -> `Plugged in` to `Active` (default)
- set `Switchable Dynamic Graphics` -> `Global Settings` -> `On battery` to `Optimize power savings`
- set `Switchable Dynamic Graphics` -> `Global Settings` -> `Plugged in` to `Optimize performance`
- set `Multimedia settings` -> `When sharing media` -> `On battery` to `Prevent idling to sleep`
- set `Multimedia settings` -> `When sharing media` -> `Plugged in` to `Prevent idling to sleep`
- set `Multimedia settings` -> `Video quality playback bias` -> `On battery` to `Video playback power-saving bias`
- set `Multimedia settings` -> `Video quality playback bias` -> `Plugged in` to `Video playback performance bias`
- set `Multimedia settings` -> `When playing video` -> `On battery` to `Balanced`
- set `Multimedia settings` -> `When playing video` -> `Plugged in` to `Optimize video quality`
- set `Battery` -> `Critical battery action` -> `On battery` to `Hibernate` (default)
- set `Battery` -> `Critical battery action` -> `Plugged in` to `Hibernate` (default)

> [!TIP]
> Leave as is the settings that are missing or hidden on your end.

## 4. Deep

### 4.1 Control Panel

`Control Panel` -> `Appearance and Personalization` -> `File Explorer Options`

- turn off `Show recently used files`
- turn off `Show frequently used folders`
- turn off `Show files from Office.com`

### 4.2 Time and language

`Time and language` -> `Typing` -> `Typing insights`

- turn off `Typing insights`

### 4.3 Privacy and security

`Privacy and security` -> `Recommendations and offers`

- turn off `Personalized offers`
- turn off `Allow websites to access my language list`
- turn off `Improve Start and search results` (turned on may help if you want to look up recents)
- turn off `Recommendations and offers in Settings`
- turn off `Advertising ID`

`Privacy and security` -> `Diagnostics and feedback`

- turn off `Diagonostic data` -> `Send optional diagnostic data`
- turn off `Improve inking and typing` -> `Improve the language recognition and suggestion capabilities of Microsoft apps and services by sending optional inking and typing diagnostic data to Microsoft`
- turn off `View diagnostic data` -> `Turn on the Diagnostic Data Viewer (uses up to 1 GB of hard drive space)`

`Privacy and security` -> `Speech`

- turn off `Online speech recognition`

### 4.4 Windows Update

`Windows Update` -> `More Options` -> `Advanced options`

- turn off `Receive updates for other Microsoft products`
- turn off `Get me up to date`

`Windows Update` -> `More Options` -> `Additional options` -> `Delivery Optimization`

- turn off `Allow downloads from other devices`

## 5. Optionals: If You Want Only Functional Visuals

### 5.1. Accessibility

`Accessibility` -> `Visual effects`

- turn off `Transparency effects`
- turn off `Animation effects`

### 5.2. System

`System` -> `About` -> `Related links` -> `Advanced system settings` -> `System Properties` -> `Advanced` -> `Performance` -> `Settings...` -> `Performance Options` -> `Visual Effects`

- select `Adjust for best performance` to toggle all of them off
- turn on `Show shadows under windows`
- turn on `Show thumbnails instead of icons`
- turn on `Show translucent selection rectangle`
- turn on `Show window contents while dragging`
- turn on `Smooth edges of screen fonts`
- turn on `Use drop shadows for icon labels on desktop`
- it'll automatically select `Custom:` for you
- click `OK`

> It should look like this:
> - [ ] `Animate controls and elements inside windows`
> - [ ] `Animate windows when minimizing and maximizing`
> - [ ] `Animations in the taskbar`
> - [ ] `Enable Peek`
> - [ ] `Fade or slide menus into view`
> - [ ] `Fade or slide ToolTips into view`
> - [ ] `Fade out menu items after clicking`
> - [ ] `Save taskbar thumbnail previews`
> - [ ] `Show shadows under mouse pointer`
> - [x] `Show shadows under windows`
> - [x] `Show thumbnails instead of icons` (default)
> - [x] `Show translucent selection rectangle` (default)
> - [x] `Show window contents while dragging` (default)
> - [ ] `Slide open combo boxes`
> - [x] `Smooth edges of screen fonts` (default)
> - [ ] `Smooth-scroll list boxes`
> - [x] `Use drop shadows for icon lables on the desktop` (default)

> [!WARNING]
> Some websites and applications such as Discord, Chrome, Edge's `Smooth scrolling` defaults depend on `Animate controls and elements inside windows`, as a result it may turn off their `Smooth scrolling` too.

> [!NOTE]
> Keeping the functional visuals so that Windows doesn't look very old from that.

## 6. Optionals: If You Want The Old Look

### 6.1 Personalization

`Personalization` -> `Taskbar` -> `Taskbar Behaviors`
- set `Taskbar alignment` to `Left`

### 6.2 Old Right-click Context Menu

- at File Explorer or Desktop, press and hold `Shift` then press `Right-click` on a blank space

> [!NOTE]
> No registry edit needed.

## 7. Others Worth to Check Briefly

### 7.1 Task View

- press and hold `Windows` key then press `Tab`
- around `+ New desktop`, check for Desktops you don't need. If you don't need them, delete it.

## The Big Three Browsers

### 1. Google Chrome

Relevant as of `2026-04-15+0000` `Version 147.0.7727.56 (Official Build) (64-bit)`

#### 1.1 Getting Started

- go to `Google Chrome` -> `Top-right vertical three-dot icon` -> `Settings`

#### 1.2 Absolute Minimum

- set `On startup` -> `On startup` to `Continue where you left off`
- turn off `System` -> `Continue running background apps when Google Chrome is closed`
- turn off `Autofill and passwords` -> `Autofill and passwords` -> `Google Password Manager` -> `Settings` -> `Settings` -> `Offer to save passwords and passkeys`

#### 1.3 A Little Deeper

- turn off `AI innovations` -> `Help me write` -> `Offer writing help`
- turn off `Languages` -> `Spell check` -> `Check for spelling errors when you type text on web pages`
- turn off `You and Google` -> `Google services` -> `Help improve Chrome's features and performance`
- turn off `You and Google` -> `Google services` -> `Make searches and browsing better`
- turn off `You and Google` -> `Google services` -> `Improve search suggestions`

#### 1.4 If You're Fine Not Having Smooth Scrolling

- `Google Chrome` -> enter the URL `chrome://flags/#smooth-scrolling`
- set `Smooth Scrolling` to `Disabled`

### 2. Microsoft Edge

Relevant as of `2026-04-15+0000` `Version 147.0.3912.60 (Official build) (64-bit)`

#### 2.1 Getting Started

`New tab` -> `Top-right gear icon` -> `Page Settings`

- turn off `Show promoted links`
- turn off `Show content`
- turn off `Show widgets`
- turn off `Show feed`
- turn off `Background`
- turn off `Show weather`

- go to `Microsoft Edge` -> `Top-right horizontal three-dot icon` -> `Settings`

#### 2.2 Absolute Minimum

- turn off `System and performance` -> `System` -> `Startup boost`
- turn off `System and performance` -> `System` -> `Continue running background extensions and apps when Edge is closed`
- set `Start, home, and new tab page` -> `On startup` to `Open tabs from the previous session`
- turn off `Passwords and autofill` -> `Passwords and autofill` -> `Microsoft Password Manager` -> `Ask to save passwords and passkeys`

#### 2.3 A Little Deeper

- turn off `Languages` -> `Writing assistance` -> `Use text prediction`
- turn off `Languages` -> `Writing assistance` -> `Use grammar and spell-check assistance`
- turn off `Privacy, search, and services` -> `Privacy` -> `Send optional diagnostic data to improve Microsoft products`
- turn off `Privacy, search, and services` -> `Privacy` -> `Help improve Microsoft products by sending the results from searches on the web`
- turn off `Privacy, search, and services` -> `Privacy` -> `Allow Microsoft to save your browsing activity including history, usage, favorites, web content, and other browsing data to personalize Microsoft Edge and Microsoft services like ads, search, shopping and news.`

#### 2.4 If You're Fine Not Having Smooth Scrolling

- `Microsoft Edge` -> enter the URL `edge://flags/#smooth-scrolling`
- set `Smooth Scrolling` to `Disabled`

### 3. Mozilla Firefox

Relevant as of `2026-04-15+0000` `149.0.2 (64-bit)`

#### 3.1 Getting Started

- go to `Mozilla Firefox` -> `Top-right horizontal three-line icon` -> `Settings`

#### 3.2 Absolute Minimum

- set `General` -> `Startup` to `Open previous windows and tabs`
- turn on `AI Controls` -> `Block AI enhancements`
- turn off `Privacy and Security` -> `Passwords` -> `Ask to save passwords`

#### 3.3 A Little Deeper

- turn off `General` -> `Spell check` -> `Check your spelling as you type`
- turn off `Firefox Data Collection and Use` -> `Send technical and interaction data to Mozilla`
- turn off `Firefox Data Collection and Use` -> `Allow Firefox to improve features, performance, and stability between updates`
- turn off `Firefox Data Collection and Use` -> `Send daily usage ping to Mozilla`

#### 3.4 If You're Fine Not Having Smooth Scrolling

- turn off `General` -> `Browsing` -> `Use smooth scrolling`
