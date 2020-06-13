# About
This is a security app that allows you to remotely control your phone. This repository contains submodules to frontend and backend code.

# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.1.3
### Added
 - Loading bar for LoginActivity
 - Loading bar for HomeActivity
 - Mechanism to save dynamic settings
 - Autofill for debug mode
 
### Changed
 - Notification priorities

### Fixed
 - DetailFragment height in AccessAnotherPhoneActivity 
 - AccessLogin opens up the same amount every time

## 0.1.4
### Added
 - Ability to change passwords

### Fixed
 - Fixed the bug in RingingAction 
 - Replaced the notification text

## 0.2.0
### Changed
 - Removed the search icon from the toolbar

### Fixed
 - All bugs related to navigation drawer
 - Navigation drawer scroll problem
 - Network notification text
 - Sometimes the navigation drawer won't have the name of the user
 - AccessAnotherPhoneActivity size of detail fragment
 - Small bug fixes

## 0.2.1
### Added
 - Save login feature
 - Added the functionality for Splash Screen Activity

### Changed
 - JSONUpdating revamped

### Fixed
 - Tons of bug fixes from the last version
 - Back stack fixes
 - Settings fixes

## 0.2.2
### Fixed
 - Sign up bug
 - JSON updating and automatic login bug

## 0.2.3
### Fixed
 - Bug fixes

## 0.2.4
### Fixed
 - Bug fixes

## 0.3.0
### Added
 - Added Splash screen
 - Added the new switch
 - Add yes or no or cancel on save notice and enter message thing
 - make the new logo
 - Put the logo everywhere, on notifications and icon
 - Added version number on splash screen if debug mode is on
 - Added front end validation for email and password

### Changed
 - Replace the old logo with the new on in access another activity login
 - Changed time window for pressing back button
 - Changed the default password in AccessAnotherPhoneLogin and Login

### Fixed
 - Fix camera activity gets stuck bug
 - Logout now stops the main networking service
 - Minor bugs with switches fixed.
 - When gridlist closes, the button of security category remains selected.
 - Enabled screen has all switches on now.
 - Fix issues with the settings not being saved sometimes due to default settings in staticsettings
 - Add the debug flag and actually make debug messages in toasts
 - Fix back pressed bugs
 - Fix image is ready notification gets stuck bug
 - Minor Bug fixes

## 0.3.1
### Added
 - Your location is being accessed by someone screen
 - Information icon to see description of actions
 - Change password functionality

### Fixed
 - Changed non debug messages to Snackbar
 - All options were on by default
 - Fixed logout backstack issue

## 0.3.2
### Fixed
 - Front camera no longer displays back camera picture
 - Minor bug fixes related to notifications, microphone

## 0.4.0
### Added
 - The new navigation drawer
 - Switch on Bluetooth action
 - Switch off Bluetooth action
 - Silent phone action
 - Medium volume phone action
 - Full ring volume phone action
 - Switch on flashlight action
 - Switch off flashlight action
 - Flashlight SOS action
 - Front end support for adding and changing phone numbers
 - SMS code for some basic actions but needs further testing
 - Added the i icon for access another phone activity
 - Fixed the height of details in access another phone activity
 - Detect battery usage, imei and sim information action
 - Added the sleeping Pi thing

### Changed
 - How MainNetworkingService functions.

### Fixed
 - Minor bug fixes
 - Fixed a few app crashes
 - Fixed material switch bug

## 0.4.1
### Fixed 
 - Fixed how permissions are requested and what happens when they are granted or not.
 - Small fixes in settings
 - Refactored and restructured spaghetti code in HomeActivityDetailListFragment

## 0.4.2
### Added
 - Snackbar on every action added
 - Your Wi-Fi state is being accessed screen

### Fixed
 - When the triple bar button is tapped open nav drawer
 - Performance improved in swipe refresh layout

## 0.4.3
### Fixed
 - Fixed the horrendous lag issue added in 0.4.1

## 0.5.0
### Added
 - Design the login screen as the access another phone activity login
 - Added date in registering and retrieving pictures
 - First time splash screen
 - Checkbox for privacy policy
 - Security for resending SMSes
 - How it works for the first time dialogs
 - Contact us in settings
 - Delete account option
 - Tutorial section in settings
 - Back end validation for email and password
 - Random token
 - Privacy policy in settings

### Fixes
 - Date format in static settings fixed
 - Did some TODOs
 - Fixed some compatibility issues
 - Tested the sms
 - Stop sending location to the server if the access location action is disabled.
 - Polished back end code, proper error handling and token 
 - Bug fixes

## 0.5.1
### Added
- Forgot password added
- Email confirmation for signup added

### Fixed
- Three line button doesn't open nav drawer
- Removed toasts
- Removed useless tutorial notes and put the (tap to dismiss) on them
- Show the how it works dialog only once
- Sometimes change enabled actions request doesn't go properly fixed
- Can't enable message actions bug fixed
- For some reason the first item in the grid, when selected, always stays selected bug fixed
