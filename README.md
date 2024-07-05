# Hide My Bar Community

![logo](https://github.com/clemstation/hide-my-bar/blob/main/img/hide-my-bar-logo.png)

## About

Your Touch Bar comes in the way of your producitivity? Worse, it's no longer in its prime and it started flickering?


[Hide My Bar](https://hidemybar.clemstation.com/) is a macOS app that allows you to turn off the Touch Bar in an instant. Simply double-tap on the key of your choice and the Touch Bar will be disabled. No more flickering. Need it for a quick action? Double-tap again to turn it back on.

## Get Started with Hide My Bar

To download and install Hide My Bar on your Mac:

1. Head over to [https://hidemybar.clemstation.com/](https://hidemybar.clemstation.com/) to grab the latest version.
2. Launch Hide My Bar from your Applications folder or Dock.
3. Choose your shortcut key and disable your Touch Bar now!

## Troubleshooting FAQ

### Why isn't Hide My Bar on the App Store?
Because of Apple's restrictions. The API used to turn off the Touch Bar is private and Apple only allows use of public APIs for apps to be published on the App Store.

### Is this safe to download and use?
This app has been notarized by Apple. It means Apple has scanned our app for malicious content and also checked for code-signing issues and approved it.
On top of that we use Sparkle’s EdDSA signature to ensure that the updates you download are the ones we published, without any alteration.

### Why is it asking me to give permissions?
In order to simulate keys pressed for Brightness, Volume and so on, you need to give the app the accessibility permissions. Go to System Preferences -> Security & Privacy -> Privacy -> Accessibility -> Check Hide My Bar.

### The Touch Bar is not hidding when using F1, F2, etc... keys, what can I do?
To be able to use the Function Keys (F1, F2, etc...) with Hide My Bar, you must change your Touch Bar configuration to either App Controls or Expanded Control Strip.
Go to System Preferences -> Keyboard. Next to Touch Bar shows, select Expanded Control Strip. Note that App Controls would work as well.
Click on Hide My Bar's icon (in the menu bar) -> Preferences -> Hot Keys and check Double tap ^Control next to Function Keys. You can choose any keys available.

### Is it working with other apps to remap keyboard or Touch Bar?
It is working well alongside Karabiner, BTT and many others. However some users reported issues using it with GoldenChaos

### I lost my license, what can I do?
FastSpring is our merchant to handle transactions and license keys delivery. Please go to their consumer support page to submit a support inquiry.

### What is Hide My Bar’s privacy policy?
We don’t collect any data. Please checkout our Privacy Policy page on our [website](https://hidemybar.clemstation.com) to read our latest policy.

## Issues and Feature requests

Go to the [Issues](https://github.com/clemstation/hide-my-bar/issues) tab to post bugs, feature requests, or questions.

Feel free to comment on any existing feature requests that you also want to request. The more requests, the more likely I'll do it.

If you're filing a bug, please include the following:

- MacOS version
- Processor (Intel, M1, ...)
- Detailed steps to reproduce

If you wish to contact me directly, feel free to send an email to [contact@clemstation.com](mailto:contact@clemstation.com).


## System Requirements

Hide My Bar is compatible with macOS 10.13 and later versions.

## Acknowledgements

Hide My Bar is built using the following open-source libraries:

- [KeyboardShortcuts](https://github.com/sindresorhus/KeyboardShortcuts)
- [LaunchAtLogin](https://github.com/sindresorhus/LaunchAtLogin-Modern)
- [Sparkle](https://github.com/sparkle-project/Sparkle)
