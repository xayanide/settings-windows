# laptop-settings-windows-11

```plaintext
v1.20260418.1
```

Relevant as of `2026-04-15+0000`.
At a minimum should work with

```plaintext
Windows 11 Home 25H2 Build 26200.8037
```

I wrote these so I have a quick reference for the changes I've been applying everytime on a fresh Windows install. Walang command line or registry edits, all within user interfaces lang. There are some default settings that are already good as is from a fresh install so they do not have to be modified. Some quick shortcuts for myself: `powercfg.cpl`, `systempropertiesadvanced`, `main.cpl`, `control`, `mmsys.cpl`, `ncpa.cpl`

## 1. Getting Started

### 1.1 Windows Settings

- Press and hold `Windows key` then press `i`.

Please follow and apply the settings as written.

## 2. Absolute Minimum

### 2.1 Privacy and security

`Privacy and security` -> `Device encryption`

> [!TIP]
> Turns off encryption and decryption of every file you open so it gives a small performance boost. We turn this off because it is an overkill security feature for a personal computer, if Windows glitches up and triggers this and you don't have the BitLocker recovery key saved, this encryption can permanently lock you out of your own files.

- turn off `Device encryption`
- click `Turn off`

`Privacy and security` -> `Device encryption` -> `BitLocker drive encryption` -> `Control Panel` -> `System and Security` -> `BitLocker Drive Encryption`

> [!TIP]
> Turns off encryption and decryption of every file you open so it gives a small performance boost. We turn this off because it is an overkill security feature for a personal computer, if Windows glitches up and triggers this and you don't have the BitLocker recovery key saved, this encryption can permanently lock you out of your own files.

-> `Operating system drive`

- turn off `BitLocker` on every drive shown, if not already
- click `Turn off BitLocker`

-> `Fixed data drives`

- turn off `BitLocker` on every drive shown, if not already
- click `Turn off BitLocker`

`Privacy and security` -> `Recall and snapshots`

> [!TIP]
> If it's there, turn it off.

- turn off `Save snapshots`

### 2.2 Bluetooth and Devices

`Bluetooth and devices` -> `Mouse`

- set `Mouse pointer speed` to `10/20` (default)

> [!TIP]
> If you wanna change your mouse sensitivity, do it inside an app or game and using your mouse's software DPI settings, not the `Mouse pointer speed`.

- turn off `Enhance pointer precision`

> [!TIP]
> We turn this off so that the movement of your cursor depends only on how far you move your mouse, not how fast you move it.

### 2.3 Accessibility

`Accessibility` -> `Keyboard` -> click `Sticky keys`, it's a dropdown

- turn off `Sticky keys` (default)
- turn off `Keyboard shortcut for Sticky keys`

`Accessibility` -> `Keyboard` -> click `Filter keys`, it's a dropdown

- turn off `Filter keys` (default)
- turn off `Keyboard shortcut for Filter keys`

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

### 2.5 Apps

`Apps` -> `Resume`

- turn off `Resume`

## 3. A Little Deeper

### 3.1 System

`System` -> `Power Mode`

- set `Plugged in` to `Balanced` (default)
- set `On battery` to `Balanced`

`System` -> `Clipboard`

- turn on `Clipboard history`

`System` -> `Advanced` -> `Taskbar`

- turn on `End Task`

`System` -> `Sound` -> `Output` -> Click `Speakers`, it's a dropdown -> `Properties`

- set `Output settings` -> `Format` to `2 channels, 24 bit, 48000 Hz (Studio Quality)`
- turn off Advanced settings `Audio enhancements`
- turn off Advanced settings `Spatial sound`

`System` -> `Sound` -> `Output` -> Click `Headphones`, it's a dropdown -> `Properties`

- set `Output settings` -> `Format` to `2 channels, 24 bit, 48000 Hz (Studio Quality)`
- turn off Advanced settings `Audio enhancements`
- turn off Advanced settings `Spatial sound`

`System` -> `Sound` -> `Input` -> Click `Microphone`, it's a dropdown -> `Properties`

- set `Output settings` -> `Format` to `2 channels, 16 bit, 48000 Hz (DVD Quality)`
- turn off Advanced settings `Audio enhancements`

`System` -> `Sound` -> `Advanced` -> `More sound settings` -> `Sound` -> `Sound`

- turn off `Program Events:` -> `Play Windows Startup sound`
- click `OK`

### 3.2 Bluetooth and devices

`Bluetooth and devices` -> `Touchpad` -> click `Touchpad`, it's a dropdown

- turn on `Leave touchpad on when a mouse is connected`

`Bluetooth and devices` -> `Keyboard` -> `Shortcuts and hotkeys`

- turn on `Use the Print screen key to open screen capture` (default)

### 3.3 Personalization

`Personalization` -> `Themes` -> `Related settings` -> `Desktop icon settings`

- turn on `Desktop icons` -> `Computer` (default)
- turn on `Desktop icons` -> `User's Files`
- turn on `Desktop icons` -> `Recycle Bin` (default)
- turn off `Allow themes to change desktop icons`

> [!TIP]
> These are most often accessed to access more things, so it kinda makes sense to always have these on desktop.

### 3.4 Time and language

`Time and language` -> `Typing`

- turn off `Show text suggestions when typing on the physical keyboard`
- turn off `Multilingual text suggestions`
- turn off `Autocorrect misspelled words`
- turn off `Highlight misspelled words`

`Time and language` -> `Date and time`

- turn on `Set time automatically` (default)
- set `Time zone` to `(UTC+08:00) Kuala Lumpur, Singapore` (varies, this is for the Philippines)

### 3.5 Control Panel

1. press the `Windows` key
2. type `control panel`
3. find it and open it
4. at top-right, set `View by:` to `Category`

`Control Panel` -> `Hardware and Sound` -> `Power Options`

- set `Selected plan` to `Balanced`

`Control Panel` -> `Hardware and Sound` -> `Power Options` -> `Selected plan` -> `Balanced` -> `Change plan settings` -> `Change advanced power settings`

- set `Hard disk` -> `Turn off hard disk after` -> `On battery (Minutes)` to `0`
- set `Hard disk` -> `Turn off hard disk after` -> `Plugged in (Minutes)` to `0`
- turn off `PCI Express` -> `Link State Power Management` -> `On battery`
- turn off `PCI Express` -> `Link State Power Management` -> `Plugged in`
- set `Processor power management` -> `Minimum processor state` -> `On battery` to `5` (default)
- set `Processor power management` -> `Minimum processor state` -> `Plugged in` to `5` (default)
- set `Processor power management` -> `Maximum processor state` -> `On battery` to `100` (default)
- set `Processor power management` -> `Maximum processor state` -> `Plugged in` to `100` (default)
- set `Switchable Dynamic Graphics` -> `Global Settings` -> `On battery` to `Optimize power savings`
- set `Switchable Dynamic Graphics` -> `Global Settings` -> `Plugged in` to `Maximize performance`

## 4. Deep

### 4.1 Control Panel

`Control Panel` -> `Appearance and Personalization` -> `File Explorer Options`

- turn off `Show recently used files`
- turn off `Show frequently used folders`
- turn off `Show files from Office.com`
- turn off `View` -> `Advanced settings:` -> `Hide extensions for known file types` or `File Explorer` -> `Top-middle list icon with "View" label` -> turn on `Show` -> `File name extensions`

### 4.2 Time and language

`Time and language` -> `Typing` -> `Typing insights`

- turn off `Typing insights`

### 4.3 System

`System` -> `About` -> `Related links` -> `Advanced system settings` -> `System Properties` -> `Advanced` -> `Startup and Recovery` -> `Settings` -> `System failure`

- turn off `Automatically restart`
- click `OK`

### 4.4 Privacy and security

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

### 4.5 Windows Update

`Windows Update` -> `More Options` -> `Advanced options`

- turn off `Receive updates for other Microsoft products`
- turn off `Get me up to date`

`Windows Update` -> `More Options` -> `Additional options` -> `Delivery Optimization`

- turn off `Allow downloads from other devices`

## Basic Browsers

### 1. Google Chrome

Relevant as of `2026-04-15+0000` `Version 147.0.7727.56 (Official Build) (64-bit)`

#### 1.1 Getting Started

- go to `Google Chrome` -> `Top-right vertical three-dot icon` -> `Settings`

#### 1.2 Absolute Minimum

- set `On startup` -> `On startup` to `Continue where you left off`
- turn off `System` -> `Continue running background apps when Google Chrome is closed`

#### 1.3 A Little Deeper

- turn off `AI innovations` -> `Help me write` -> `Offer writing help`
- turn off `Languages` -> `Spell check` -> `Check for spelling errors when you type text on web pages`
- turn off `You and Google` -> `Google services` -> `Help improve Chrome's features and performance`
- turn off `You and Google` -> `Google services` -> `Make searches and browsing better`
- turn off `You and Google` -> `Google services` -> `Improve search suggestions`

### 2. Microsoft Edge

Relevant as of `2026-04-15+0000` `Version 147.0.3912.60 (Official build) (64-bit)`

#### 2.1 Getting Started

- go to `Microsoft Edge` -> `Top-right horizontal three-dot icon` -> `Settings`

#### 2.2 Absolute Minimum

- turn off `System and performance` -> `System` -> `Startup boost`
- turn off `System and performance` -> `System` -> `Continue running background extensions and apps when Edge is closed`
- set `Start, home, and new tab page` -> `On startup` to `Open tabs from the previous session`

#### 2.3 A Little Deeper

- turn off `Languages` -> `Writing assistance` -> `Use text prediction`
- turn off `Languages` -> `Writing assistance` -> `Use grammar and spell-check assistance`
- turn off `Privacy, search, and services` -> `Privacy` -> `Send optional diagnostic data to improve Microsoft products`
- turn off `Privacy, search, and services` -> `Privacy` -> `Help improve Microsoft products by sending the results from searches on the web`
- turn off `Privacy, search, and services` -> `Privacy` -> `Allow Microsoft to save your browsing activity including history, usage, favorites, web content, and other browsing data to personalize Microsoft Edge and Microsoft services like ads, search, shopping and news.`

### 3. Mozilla Firefox

Relevant as of `2026-04-15+0000` `149.0.2 (64-bit)`

#### 3.1 Getting Started

- go to `Mozilla Firefox` -> `Top-right horizontal three-line icon` -> `Settings`

#### 3.2 Absolute Minimum

- set `General` -> `Startup` to `Open previous windows and tabs`
- turn on `AI Controls` -> `Block AI enhancements`

#### 3.3 A Little Deeper

- turn off `General` -> `Spell check` -> `Check your spelling as you type`
- turn off `Firefox Data Collection and Use` -> `Send technical and interaction data to Mozilla`
- turn off `Firefox Data Collection and Use` -> `Allow Firefox to improve features, performance, and stability between updates`
- turn off `Firefox Data Collection and Use` -> `Send daily usage ping to Mozilla`
