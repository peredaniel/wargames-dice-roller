# Wargames Dice Roller

This is the public repository for the utility app _Wargames Dice Roller_.

This is the English version of the README. We also have a [Spanish](README_Spanish.md) and a [Catalan](README_Catalan.md) versions available.

## Reporting bugs and asking for new features

Do you have any ideas for future developments? Did you find a nasty bug that escaped our testing team? If you do have a GitHub account, please feel free to open an issue with your idea or your bug!

When reporting a bug, please include as much relevant non-personal information as possible, such as device model, iOS/Android version and app version (can be found in "Settings" tab).

## Privacy policy

This privacy policy governs your use of the software application _Wargames Dice Roller_ ("Application") for iOS and Android devices.

### What information does the Application obtain and how is it used?

The app does not obtain any kind of information, neither from the device or the app usage.

### Changes

This Privacy Policy may be updated from time to time for any reason. We will notify you of any changes to our Privacy Policy by posting the new Privacy Policy here and informing you via this website. You are advised to consult this Privacy Policy regularly for any changes, as continued use is deemed approval of all changes.

## Availability and compatibility

[View in the AppStore](https://apps.apple.com/app/wargames-dice-roller/id6448962936)

[View in the PlayStore](https://play.google.com/store/apps/details?id=com.prietomartinez.wargamesdiceroller)

The iOS app is currently compatible with **iPhone devices running iOS 17 or higher**. The Android app is compatible with devices running **Android 9 or higher**. Both are available in the following stores:
* Europe (all countries)

## Version history

### iOS

#### Version 1.5.2

* Fixed a critical issue causing the app to close unexpectedly when a roll within a series had no dices to roll as a result of a previous roll.

#### Version 1.5.1

* Fixed an issue causing the roll description not to update when updating its type for a roll series.

#### Version 1.5

* Adapted user interface for Liquid Glass UI.
* Code optimizations and improved performance.
* Increase minimum iOS version to 17.

#### Version 1.4

* New features:
    - Added functionality to perform a sequence of rolls.
    - Redesigned "Roll history" to include "Roll series".
    - Aligned user interface with Android app.

* Bugfixes:
    - Minor bug fixes and optimizations.

#### Version 1.3

* New features:
	- Added functionality to store several roll configurations in "Settings" to be used in the "Roll dices" tab.
	- Added functionality in "Settings" to change the default roll configuration in use in the "Roll dices" tab.
	- Added a menu to select the roll configuration to be used in the "Roll dices" tab.

* Bugfixes:
	- Fixed an issue causing the app to crash when selecting a dice type with a number of faces lower than the current success threshold in the roll settings screen.
	- Fixed an issue causing the app to not update the critical threshold value when changing selected dice type to a type with a number of faces lower than the current value.

#### Version 1.2

* Implemented user guides on several screens.

#### Version 1.1.1

* Fix some errors on localized texts arising from the previous update.

#### Version 1.1

* New features:
	- Added functionality to add or subtract a value to the result of a "sum dice values" roll (between 0 and 15).
	- Added functionality to define successes and criticals with comparisons of the type "greater or equal than", "equal to" and "lower or equal than" a dice value. Compatible with D20 games such as Infinity®.

* Bugfixes:
	- Fixed computation of successes and criticals: now criticals are a particular case of successes, rather than an independent result.
	- Fixed some translations typos.
	- Fixed an issue causing the History Log to be sorted incorrectly.

#### Version 1.0

Initial app release.

* Features included:
	- Dice roller feature to perform a single roll with multiple dices.
	- Result feature to compute different outcomes from the roll, including summing results, concatenating and counting successes/failures with thresholds.
	- Feature to add post-roll steps to the roll, such as adding/discarding dices, rerolls or replacements.
	- Persistance for rolls, either to consult them or to perform a new roll with the same parameters.
	- Settings allow to define a default roll that will prefill the roll parameters. They may always be changed before rolling.

### Android

#### Version 1.5.2

* Fixed an issue causing the UI to not display properly details for rolls within a series that had no dices to roll as a result of a previous roll.

#### Version 1.5.1

* Fixed an issue causing the roll description not to update when updating its type for a roll series.
* Fixed wrong header in roll configurations list.

#### Version 1.5

* Code optimizations and improved performance.

#### Version 1.4.1

* Fixed an issue causing some Roll Series to not be deleted when clearing the Roll History.

#### Version 1.4

* New features:
    - Added functionality to perform a sequence of rolls.
    - Redesigned "Roll history" to include "Roll series".
    - Aligned user interface with iOS app.

* Bugfixes:
    - Minor bug fixes and optimizations.

#### Version 1.3

* New features:
	- Added functionality to store several roll configurations in "Settings" to be used in the "Roll dices" tab.
	- Added functionality in "Settings" to change the default roll configuration in use in the "Roll dices" tab.
	- Added a menu to select the roll configuration to be used in the "Roll dices" tab.

* Bugfixes:
	- Fixed an issue causing the app to crash when selecting a dice type with a number of faces lower than the current success threshold in the roll settings screen.
	- Fixed an issue causing the app to not update the critical threshold value when changing selected dice type to a type with a number of faces lower than the current value.

#### Version 1.2.1

* Fixed an issue causing the stepper to increase or decrease success and critical values not appearing for "Successes / failures" rolls.

#### Version 1.2

* Implemented swipe to delete steps in post-roll sequence.
* Implemented reordering of steps in post-roll sequence.

#### Version 1.1

* Implemented user guides on several screens.
* Added animations when interacting with some screen elements to improve user experience.
* Fixed a bug causing the bottom and top bars to appear translucent. 

#### Version 1.0

Initial app release. Equivalent to iOS version 1.1.1.

* Features included:
	- Dice roller feature to perform a single roll with multiple dices.
	- Result feature to compute different outcomes from the roll, including summing results, concatenating and counting successes/failures with thresholds.
	- Feature to add post-roll steps to the roll, such as adding/discarding dices, rerolls or replacements.
	- Persistance for rolls, either to consult them or to perform a new roll with the same parameters.
	- Settings allow to define a default roll that will prefill the roll parameters. They may always be changed before rolling.
	- Feature to add or subtract a value to the result of a "sum dice values" roll (between 0 and 15).
	- Feature to define successes and criticals with comparisons of the type "greater or equal than", "equal to" and "lower or equal than" a dice value. Compatible with D20 games such as Infinity®.