# Changelog
All notable changes to this project will be documented in this file.

## [1.2.3]
- ## Features
- Added a log category popup before adding a new log ready for different log types.
- Organisations now show a live list of team members, click on members for more details.
- New filter area on the home screen.
- View the detailed changelog within the app on the settings screen.
- ## Bug Fixes
- Background images now do not get squished when the keyboard appears on auth screens.
- Password fields are now clear when submitted.
- Light theme inconsistencies fixed.
- Text now capitalises at the start of new sentences. 
- Bottom Nav padding is now consistent with the device type.
- ## Building
- Updated Dart SDK to enable null safety.
- Updated pod file.
- Updated packages.
- Updated Gradle.

## [1.2.2]
- ## Features
- Enabled SARLog for the web.
- Made SARLog responsive for the web.
- Updated pdf layout.
- Moved leave team button to appbar.
- Moved add dog button.
- Added License Page.
- ## Bug Fixes
- 
- ## Building
- Improved state management on organisations.


## [1.2.1]
- ## Features
- Removed icon on log cards.
- ## Bug Fixes
- Fixed an issue where you were unable to input decimal points.
- ## Building
- Updated packages.
- Updated podfile.
- Removed unused imports.
- Folder/file name changes.

## [1.2.0]
- ## Features
- Light theme added and now can toggle between Dark/Light mode.
- New settings area within the profile page.
- Added log identifer within log view page.
- New success message popup.
- Dog Profile/Add Dog now opens in a cleaner way.
- Layout changes for tablet users.
- ## Bug Fixes
- Fixed an issue where the password would not get validated within settings.
- ## Building
- Updated packages.
- Updated podfile.
- Removed unused imports.
- Folder/file name changes.

## [1.1.7]
- ## Features
- Organisations can be registered.
- Now have the ability to change map type in expanded map view on logs.
- Leaving team confirmation introduced.
- UserID now shows on the profile page.
- Added shimmer to some text.
- ## Bug Fixes
- Fixed an issue where the user would be logged out however app would not show to be logged out.
- Fixed an issue where user information will be cleared if they joined an organisation.
- Keyboard now does not block fields on organisation registration.  
- ## Building
- Lint rules introduced to project, code has been modified to follow rules.
- All packages have been updated to the latest versions.
- Code has been modified to use new/renamed functions from packages.
- Reusables file created for common widgets.

## [1.1.6]
- Users will be able to create an organisation

## [1.1.5]
- Fixed bug where new logs would not save and instead crash the app.

## [1.1.4]
- Added Apple login for iOS.
- Users can join an organisation, but it currently does not have any functionality.
- Users can leave an organisation.
- Fixed a bug where the current email was not showing when trying to change email.
- Changed background colour for icon on main cards. 

## [1.1.3+14] 
- Resized log icons on main cards.
- Leaving a team refreshes the app and user is removed from team.

## [1.1.3+13] 
- Removed Push Notifications.

## [1.1.3+12] 
- Code cleanup.
- PDF Generation now contains all data user can input.
- Duration on log screen updated for user readability.
- Icons added on main cards for logs to determine what log type they are ready for future updates.

## [1.1.3+11] 
- Updated code colour identifiers

## [1.1.3+10] 
- Banner introduced on Organisation page to show it is under development.
- App Icons + Logos redesigned.
- Log cards on home screen redesigned to remove whitespace.
- Maps are now cached when map tiles have been loaded.

## [1.1.3+9]
- Removed home screen popup.
- Some message changes.

## [1.1.3+8]
- Popup now displays on home screen if user is new.

## [1.1.2]
- Users can now join an org with the correct pin (Cannot currently create a org or leave one).
- New users are greeted with an example log on the home page.
- Logs have new information fields dependent on log type and search type.
- Will now only be able to put digits into numeric text fields and not A-Z or special characters. 
- Authentication screens are now scrollable when the keyboard is active.
- Merged the image sections on the log screens to keep simplicity.
- You now get prompted to save the log if you have edited one but have pressed the back button.
- Users who signin with Google now do not lose their profile pictures if they relogin.
- Dog selection now only shows if you are a dog handler (Have a dog on the system).
- Some messages have been rewritten.
- UI changes on log screen.

## [1.1.1+4]
- HOTFIX to fix blank screen on android release.

## [1.1.1]
- HOTFIX to fix a bug where the camera would not open on Android 11+.

## [1.1.0]
- PDF generation is here!
    You can now easily generate a PDF of any log by viewing the log and clicking the PDF icon within the floating button.
    PDFs are automatically generated and then shown for you to choose to either save, share or print them.
    (PDFs will be improved throughout time)
- App checks to see if the device has any network connection before attempting to save a log.
- Log images are now cached for data saving & offline use.  
- Updated help page.
    

## [1.0.1]
- App now runs smoothly on the latest version of Flutter (2.5.1).
- Removed date range picker package due to depreciation.
- Transferred to native Flutter DateRangePicker on the home screen.
- Implemented a colour scheme on themeData due to Flutter 2.5.0
- Removed Android background location permission.
- Updated Google scheme for iOS Login to work.

## [1.0.0]
- Version 1.0.0 RELEASED to Playstore
- Fixed bug where if a log has a long description it would all show on the main screen.

## 09-09-2021
- PDF Generation for logs initated

## 02-09-2021
- Toggle Tabs now replace some dropdowns in log information.

## 25-08-2021
- Profile & Dog images are now cached for data saving & offline use.
- Organisation pins padding reworked.

## 23-08-2021
- Updated packages

## 08-08-2021
- Converted to Mapbox Maps from Google Maps.
- Inplemented Performance Monitoring (Firebase).
- Organisation UI placeholders.

## 02-08-2021
- Log filtering now works on the home screen.
- Log filtering options are removed when the user selects a date range.
- Logs are now ordered by date with inApp code and not a firebase query.
- Log cards are now implemented in the dogloglist file.
- logType list now has default values incase of null follow throughs. 
- Removed unused code from log_database.

## 27-07-2021
- Reset button now appears on home log screen when user selects dates.
- Updated min and target sdk versions for Android.

## 24-07-2021
- Weather information in log screen more formatted.
- Added more dog levels on dog profile.
- Mapview on logs now contain exit button for the user to get out of the map.

## 12-07-2021
- Log home screen now redesigned to me more cleaner.
- Date selection picker is now accessed from app bar on the right hand side.
- Updated podfile for iOS.

## 04-07-2021
- Updated console messages to better repesent whats happening.
- Keyboard should now unfocus whenever user clicks off it.

## 01-07-2021
- Updated packages

## 02-06-2021
- Now checks to see if user is an organisation and displays correct screen
- Team UI creation

## 29-05-2021
- Started organisation pin entry for users who are not in an organisation.

## 18-05-2021
- Changed flushbar package to alternative due to other one being discontinued.

## 18-05-2021
- NoScroll added to log selector

## [0.2.0.1] - 11-05-2021
- Added correct keyboard types for all textfields.
- Fixed a issue where the keyboard will still show when trying to add images.
- Readded help screen.
- Help page updated.

## 05-05-2021
- Fixed error on log page if no dog was selected whilst creating log.
- Removed drawer and implemented bottom nav bar.
- Font changed to Ubuntu.
- Removed firstLoad on logs screen due to botton navigation.
- Converted floating button to appbar on logs screen
- Added .trim() to important text fields to remove accidental whitespace
- Settings screen now within profile.
- Screens are now persistent when switching between & scrollable.

## 27-03-2021
- Ability to change email added to settings page.
- Ability to change password added to settings page.
- entryField widget now does not require a title.
- Minor UI changes on Log & Dog screens.

## 27-03-2021
- Initiated changelog.
- Fixed bug where user id was not being passed through to add log screen when the user was using the drawer to navigate.
- Add/Edit Dog removed drawer button and replaced with back button.
- Log screens removed drawer button and replaced with back button.
- Removed unused imports.
- Cleaned imports (More readable).
