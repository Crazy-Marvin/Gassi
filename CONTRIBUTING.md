# Contributung to Gassi

👍🎉 First off, thanks for taking the time to contribute! 🎉👍

The following is a set of guidelines for contributing to Gassi, which are hosted on [GitHub](https://github.com/Crazy-Marvin/Gassi). These are just guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## What should I know before I get started?

### Code of Conduct

This project adheres to the [Contributor Covenant code of conduct](https://contributor-covenant.org/version/1/4/).
By participating, you are expected to uphold this code. Please report unacceptable behavior to [marvin@poopjournal.rocks](mailto:marvin@poopjournal.rocks).

### Contact

If you have any questions or are unsure about something just drop a line to [marvin@poopjournal.rocks](mailto:marvin@poopjournal.rocks).

### Design Decisions

If you plan to make a significant decision in how to maintain the project and what it can or cannot support please send an email beforehand. 

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for [Gassi](https://poopjournal.rocks/Gassi/) software. Following these guidelines helps maintainers and the community understand your report 📝, reproduce the behavior 📱💻🎮, and find related reports 🔎.

Before creating bug reports, please check this list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for [Gassi](https://poopjournal.rocks/Gassi/), including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion 📝 and find related suggestions 🔎.

Before creating enhancement suggestions, please check this list as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please include as many details as possible.

### Pull Requests

+ Include screenshots and animated GIFs in your pull request whenever possible.
+ Create a [branch](https://guides.github.com/introduction/flow/) for your edit
    
### Git Commit Messages

+ Use the present tense ("Add feature" not "Added feature")
+ Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
+ Limit the first line to 72 characters or less
+ Reference issues and pull requests liberally
+ When only changing documentation, include [ci skip] in the commit description
+ Consider starting the commit message with an applicable emoji:

        🎨 :art: when improving the format/structure of the code
        🐎 :racehorse: when improving performance
        🚱 :non-potable_water: when plugging memory leaks
        📝 :memo: when writing docs
        🐧 :penguin: when fixing something on Linux
        🍎 :apple: when fixing something on macOS
        🏁 :checkered_flag: when fixing something on Windows
        🐛 :bug: when fixing a bug
        🔥 :fire: when removing code or files
        💚 :green_heart: when fixing the CI build
        ✅ :white_check_mark: when adding tests
        🔒 :lock: when dealing with security
        ⬆️ :arrow_up: when upgrading dependencies
        ⬇️ :arrow_down: when downgrading dependencies
        👕 :shirt: when removing linter warnings
        

# Setup

## Flutter/Dart

### Linux

- Check your [System Requirements](https://flutter.dev/docs/get-started/install/linux/)
- Download the Flutter SDK
- Extract the Flutter SDK in the desired location
- Add ```flutter``` to your path
- Download [Android Studio](https://developer.android.com/studio) (preferrably using the [JetBrains Toolbox](https://www.jetbrains.com/toolbox/app/))
- Set up your Android device/emulator 
- Install Flutter/Dart plugins in [Android Studio](https://developer.android.com/studio), [IntelliJ IDEA Ultimate](https://www.jetbrains.com/idea/), [VS Code](https://code.visualstudio.com/) or any another editor (the three linked editors are supported officially, but almost all other editors have community support for Flutter/Dart)
- Run ```flutter doctor``` to see if everything worked out fine

- *Optional*: Disable analytics using ```flutter config --no-analytics```
- *Optional*: Install [JetBrains IntelliJ IDEA Ultimate](https://www.jetbrains.com/idea/) using JetBrains Toolbox, [VS Code](https://code.visualstudio.com/) or any other IDE/text editor

### macOS

- Check your [System Requirements](https://flutter.dev/docs/get-started/install/macos/)
- Download the Flutter SDK
- Extract the Flutter SDK in the desired location
- Add ```flutter``` to your path
- Download [Android Studio](https://developer.android.com/studio) (preferrably using the [JetBrains Toolbox](https://www.jetbrains.com/toolbox/app/)) and [Xcode](https://developer.apple.com/xcode/)
- Set up your Android & iOS/iPadOS devices/emulators 
- Install Flutter/Dart plugins in [Xcode](https://developer.apple.com/xcode/), [Android Studio](https://developer.android.com/studio), [IntelliJ IDEA Ultimate](https://www.jetbrains.com/idea/), [VS Code](https://code.visualstudio.com/) or any another editor (the linked editors are supported officially, but almost all other editors have community support for Flutter/Dart)
- Run ```flutter doctor``` to see if everything worked out fine

- *Optional*: Disable analytics using ```flutter config --no-analytics```
- *Optional*: Install [JetBrains IntelliJ IDEA Ultimate](https://www.jetbrains.com/idea/) using JetBrains Toolbox, [VS Code](https://code.visualstudio.com/) or any other IDE/text editor

### Windows

- Check your [System Requirements](https://flutter.dev/docs/get-started/install/windows/)
- Download the Flutter SDK
- Extract the Flutter SDK in the desired location
- Add ```flutter``` to your path
- Download [Android Studio](https://developer.android.com/studio) (preferrably using the [JetBrains Toolbox](https://www.jetbrains.com/toolbox/app/))
- Set up your Android device/emulator 
- Install Flutter/Dart plugins in [Android Studio](https://developer.android.com/studio), [IntelliJ IDEA Ultimate](https://www.jetbrains.com/idea/), [VS Code](https://code.visualstudio.com/) or any another editor (the three linked editors are supported officially, but almost all other editors have community support for Flutter/Dart)
- Run ```flutter doctor``` to see if everything worked out fine

- *Optional*: Disable analytics using ```flutter config --no-analytics```
- *Optional*: Install [JetBrains IntelliJ IDEA Ultimate](https://www.jetbrains.com/idea/) using JetBrains Toolbox, [VS Code](https://code.visualstudio.com/) or any other IDE/text editor

The final result should look like that:
[]

More information can be obtained from [https://flutter.dev/docs/get-started/install/](https://flutter.dev/docs/get-started/install/).

## Firebase

Gassi uses [Firebase](https://firebase.google.com/) [Cloud Firestore](https://firebase.google.com/products/firestore/), [Authentification](https://firebase.google.com/products/auth/), [Hosting](https://firebase.google.com/products/hosting/), [Cloud Storage](https://firebase.google.com/products/storage/), [Realtime Database](https://firebase.google.com/products/realtime-database/), [Crashlytics](https://firebase.google.com/products/crashlytics/), [Performance Monitoring](https://firebase.google.com/products/performance/), [Test Lab](https://firebase.google.com/products/test-lab/), [In-App-Messaging](https://firebase.google.com/products/in-app-messaging/), [Google Analytics](https://firebase.google.com/products/analytics/), [Cloud Messaging](https://firebase.google.com/products/cloud-messaging/), [Remote Config](https://firebase.google.com/products/remote-config/) and [Dynamic Links](https://firebase.google.com/products/dynamic-links/).

Please create your own platform-specific Firebase configuration for development.

# __Thank you so much! 😘__

