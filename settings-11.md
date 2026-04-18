# windows-11-settings

Relevant as of `2026-04-15+0000`.
At a minimum should work with

```
Windows 11 Home 25H2 Build 26200.8037
```

Open Windows Settings.

- Press and hold `Windows key` then press `i`.

Please follow and apply the settings as written.

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

`System` -> `Power Mode`

- set `Plugged in` to `Balanced`
- set `On battery` to `Balanced`

`Bluetooth and devices` -> `Mouse`

- set `Mouse pointer speed` to `10/20`
- turn off `Enhance pointer precision`

`Bluetooth and devices` -> `Keyboard` -> `Shortcuts and hotkeys`

- turn on `Use the Print screen key to open screen capture`

`Personalization` -> `Themes` -> `Related settings` -> `Desktop icon settings`

- turn on `Desktop icons` -> `Computer`
- turn on `Desktop icons` -> `User's Files`
- turn on `Desktop icons` -> `Recycle Bin`
- turn off `Allow themes to change desktop icons`
  These are most often accessed to access more things, it makes sense for these to always appear on desktop.

`System` -> `Clipboard`

- turn on `Clipboard history`

`Accessibility` -> `Mouse`

- turn off `Hide pointer while typing`

`Accessibility` -> `Visual effects`

- turn on `Always show scrollbars`

`Accessibility` -> `Keyboard`

- turn off `Sticky keys`
- turn off `Filter keys`
- turn off `Toggle keys`

`Accessibility` -> `Keyboard` -> click `Sticky keys`, it's a dropdown

- turn off `Keyboard shortcut for Sticky keys`

`Accessibility` -> `Keyboard` -> click `Filter keys`, it's a dropdown

- turn off `Keyboard shortcut for Filter keys`

`Accessibility` -> `Narrator`

- turn off `Keyboard shortcut for Narrator`

`Bluetooth and devices` -> `Touchpad` -> click `Touchpad`, it's a dropdown

- turn on `Leave touchpad on when a mouse is connected`

`Time & language` -> `Typing`

- turn off `Show text suggestions when typing on the physical keyboard`
- turn off `Multilingual text suggestions`
- turn off `Autocorrect misspelled words
- turn off `Highlight misspelled words`

`Privacy & security` -> `Device encryption`

- turn off `Device encryption`
- click `Turn off`

`Privacy and security` -> `Device encryption` -> `BitLocker drive encryption`

`Operating system drive`

- On every drive shown, turn off `BitLocker` if not already
- Click `Turn off BitLocker`

`Fixed data drives`

- On every drive shown, turn off `BitLocker` if not already
- Click `Turn off BitLocker`

`Privacy & security` -> `Recall and snapshots`

- turn off `Save snapshots`

`Apps` -> `Resume`

- turn off `Resume`

`Control Panel` -> `Power Options`

- set `Selected plan` to `Balanced`

`Control Panel` -> `Power Options` -> `Choose what the power buttons do` -> `Change settings that are currently unavailable` -> `User Account Control`

- click `Yes` if prompted
- turn off `Turn on fast startup (recommended)`
- click `Save changes`

`Control Panel` -> `Power Options` -> `Selected plan` -> `Balanced` -> `Change plan settings` -> `Change advanced power settings`

- set `Hard disk` -> `Turn off hard disk after` -> `On battery (Minutes)` to `0`
- set `Hard disk` -> `Turn off hard disk after` -> `Plugged in (Minutes)` to `0`
- turn off `PCI Express` -> `Link State Power Management` -> `On battery`
- turn off `PCI Express` -> `Link State Power Management` -> `Plugged in`
- set `Processor power management` -> `Minimum processor state` -> `On battery` to `5`
- set `Processor power management` -> `Minimum processor state` -> `Plugged in` to `5`
- set `Processor power management` -> `Maximum processor state` -> `On battery` to `100`
- Set `Processor power management` -> `Maximum processor state` -> `Plugged in` to `100`
- Set `Switchable Dynamic Graphics` -> `Global Settings` -> `On battery` to `Optimize power savings`
- set `Switchable Dynamic Graphics` -> `Global Settings` -> `Plugged in` to `Maximize performance`

# The following below can be left unchanged, you may apply them for completeness

`Control Panel` -> `Appearance and Personalization` -> `File Explorer Options`

- turn off `Show recently used files`
- turn off `Show frequently used folders`
- turn off `Show files from Office.com`
- turn off `View` -> `Advanced settings:` -> `Hide extensions for known file types` or `File Explorer` -> `Top-middle list icon with "View" label` -> turn on `Show` -> `File name extensions`

`Time & language` -> `Typing` -> `Typing insights`

- turn off `Typing insights`

`Privacy & security` -> `Recommendations and offers`

- turn off `Personalized offers`
- turn off `Allow websites to access my language list`
- turn off `Improve Start and search results` (can help a bit if turned on)
- turn off `Recommendations and offers in Settings`
- turn off `Advertising ID`

`Privacy & security` -> `Diagnostics and feedback`

- turn off `Diagonostic data` -> `Send optional diagnostic data`
- turn off `Improve inking and typing` -> `Improve the language recognition and suggestion capabilities of Microsoft apps and services by sending optional inking and typing diagnostic data to Microsoft`
- turn off `View diagnostic data` -> `Turn on the Diagnostic Data Viewer (uses up to 1 GB of hard drive space)`

`Privacy & security` -> `Speech`

- turn off `Online speech recognition`

`System` -> `About` -> `Related links` -> `Advanced system settings` -> `System Properties` -> `Advanced` -> `Startup and Recovery` -> `Settings` -> `System failure`

- turn off `Automatically restart`
- click `OK`

`Windows Update` -> `More Options` -> `Advanced options`

- turn off `Receive updates for other Microsoft products`
- turn off `Get me up to date`

`Windows Update` -> `More Options` -> `Additional options` -> `Delivery Optimization`

- turn off `Allow downloads from other devices`

## non-windows related

### Google Chrome

`2026-04-15+0000`
`Version 147.0.7727.56 (Official Build) (64-bit)`

`Google Chrome` -> `Top-right vertical three-dot icon` -> `Settings`

- set `On startup` -> `On startup` to `Continue where you left off`
- turn off `System` -> `Continue running background apps when Google Chrome is closed`
- turn off `AI innovations` -> `Help me write` -> `Offer writing help`
- turn off `Languages` -> `Spell check` -> `Check for spelling errors when you type text on web pages`
- turn off `You and Google` -> `Google services` -> `Help improve Chrome's features and performance`
- turn off `You and Google` -> `Google services` -> `Make searches and browsing better`
- turn off `You and Google` -> `Google services` -> `Improve search suggestions`

### Microsoft Edge

`2026-04-15+0000`
`Version 147.0.3912.60 (Official build) (64-bit)`

`Microsoft Edge` -> `Top-right horizontal three-dot icon ` -> `Settings`

- turn off `System and performance` -> `System` -> `Startup boost`
- turn off `System and performance` -> `System` -> `Continue running background extensions and apps when Edge is closed`
- set `Start, home, and new tab page` -> `On startup` to `Open tabs from the previous session`
- turn off `Languages` -> `Writing assistance` -> `Use text prediction`
- turn off `Languages` -> `Writing assistance` -> `Use grammar and spell-check assistance`
- turn off `Privacy, search, and services` -> `Privacy` -> `Send optional diagnostic data to improve Microsoft products`
- turn off `Privacy, search, and services` -> `Privacy` -> `Help improve Microsoft products by sending the results from searches on the web`
- turn off `Privacy, search, and services` -> `Privacy` -> `Allow Microsoft to save your browsing activity including history, usage, favorites, web content, and other browsing data to personalize Microsoft Edge and Microsoft services like ads, search, shopping and news.`

### Mozilla Firefox

`2026-04-15+0000`
`149.0.2 (64-bit)`

`Mozilla Firefox` -> `Top-right horizontal three-line icon` -> Settings

- set `General` -> `Startup` to `Open previous windows and tabs`
- turn on `AI Controls` -> `Block AI enhancements`
- turn off `General` -> `Spell check` -> `Check your spelling as you type`
- turn off `Firefox Data Collection and Use` -> `Send technical and interaction data to Mozilla`
- turn off `Firefox Data Collection and Use` -> `Allow Firefox to improve features, performance, and stability between updates`
- turn off `Firefox Data Collection and Use` -> `Send daily usage ping to Mozilla`
