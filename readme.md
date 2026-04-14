# MacTube (Enhanced Fork)

![MacTube](https://i.imgur.com/IdCeRJF.png)

MacTube is a fast, lightweight WebKit wrapper for YouTube on macOS. It was made for people who prefer Safari and don't want to open Chrome just to launch the official web app.

**This fork adds major improvements over the original version:**
- **Picture-in-Picture (PiP) Support:** Right-click twice on a video and select "Enter Picture-in-Picture" to watch videos while you work.
- **Native Fullscreen Support:** Properly takes advantage of the WebKit fullscreen API for a true immersive experience.

## Download

You can download the latest `.zip` release directly from this repository, or build the application from source using Xcode.

## Malicious Software Warning

When you try and open MacTube for the first time, you might get this error:

> “MacTube” can’t be opened because Apple cannot check it for malicious software.

Just click `OK`, then go to `System Settings -> Privacy & Security`, and click the `Open Anyway` button.
This app does not contain a virus; this warning appears because the app is signed locally or not with a commercial Apple Developer certificate.

## Contributing

This app was created natively with SwiftUI.
If you would like to add a feature, please feel free to submit a PR!
