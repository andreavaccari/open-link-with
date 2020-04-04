# Open Link With

*A simple AppleScript app to choose how to open a link from any app on macOS.*

<p align="center">
  <img width="480" src="assets/open-link-with.png?raw=true">
</p>

Normally, when clicking on a link from an app, a new tab is created in the most recent window of the default browser.

Open Link With let's you choose whether to use an existing or a new window, in either standard or incognito mode.

For convenience, it also allows to open links in Safari.

## Install

**Step 1.** [Download `Open Link With.app`](https://github.com/andreavaccari/open-link-with/releases/download/v1.0/Open-Link-With.zip) and save it in a location of your choice.

**Step 2.** Install SwiftDefaultApps with `brew cask install swiftdefaultappsprefpane`

**Step 3.** Set `Open Link With.app` as default browser in System Preferences > SwiftDefaultApps.

<p align="center">
  <img width="480" src="assets/swiftdefaultapps.png?raw=true">
</p>

**Note.** If you receive a security alert by macOS, go to System Preferences > Security & Privacy and click "Open anyway".

## Modify

To modify the app, open it with macOS' Script Editor in `/System/Applications/Utilities`.

## Resources

- [`SwiftDefaultApps`](https://github.com/Lord-Kamina/SwiftDefaultApps) by [Lord-Kamina](https://github.com/Lord-Kamina)
- The idea of using AppleScript and SwiftDefaultApps is discussed in a [Medium post](https://medium.com/@eugenkiss/protip-open-links-in-a-new-chrome-window-on-macos-afb71a2a78f7) by [Eugen Kiss](https://medium.com/@eugenkiss).
- The Google Chrome command line switches used in the app are discussed [here](https://peter.sh/experiments/chromium-command-line-switches/) and [here](https://apple.stackexchange.com/questions/305901).
