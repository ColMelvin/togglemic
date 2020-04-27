# togglemic

An AppleScript workflow that toggles the internal mic's input volume on OS X.

Original idea from: http://superuser.com/a/397770/40768

## Features

* Displays notifications to validate actions
* Stores volume level before mute for use when un-muting
* Each device and input stream stores a different volume level
* Uses native AppleScript
* Does not require any additional permissions

## Setup

### Create Action

1. Open Automator.
1. Create new Quick Action.
1. Set "Workflow receives current" to "no input" in "any application".
1. Add "Run AppleScript"
1. Copy contents of togglemic.applescript into text box
1. Save Quick Action.

### Assign Hotkey

1. Open System Preferences.
1. Select Keyboard page.
1. Select Shortcuts tab.
1. Select Services item in left selecton box.
1. In the right selection box, under "General", click on the saved Quick Action.
1. Press keys to use for hotkey

I like Fn+Shift+F10.  It uses the same button as "mute speakers" and, requiring
Shift means that applications can still use F10 by itself for functionality.
