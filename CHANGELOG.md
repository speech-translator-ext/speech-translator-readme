# Changelog

## v1.0.0

- Add unified support for multiple payment providers (Patreon, Boosty, and Stripe)
- Add Audio Source Selection with options for Current Tab, Desktop Audio Capture, and Input Audio Device
- Add an "Override default audio input" option to select a specific recording device
- Add AI Voice Isolation feature
- Add Offline Speech Recognition (Chrome only)
- Add Compact View Mode for subtitle-style text display with dynamically calculated display timing
- Add Translation Read Aloud feature
- Add Second Language Translation to display two translations simultaneously using independent translation services
- Add new translation engines: Yandex, DeepL, Bing (also as interim), VolcTrans, Youdao, and Sogou
- Update the Release Notes UI to an interactive, slide-based layout
- Update all packages to their latest versions
- Update Google Translate (Script) to use POST method requests
- Add profile, login, and reset password pages
- Add version migration logic for the extension
- Refactor all storage settings to use the "local" storage type
- Add premium status check functionality
- Add a "Test Speech Recognition Engine" tool to the Instructions
- Unify error handling during audio capture (e.g., missing microphone permissions)
- Secure audio capture inside iframes
- Add promotional message displays for Streaming Mode
- Implement a smart queue for translation requests with auto-aborting based on delay drift
- Add an alert window regarding browser support
- Update the Instructions to reflect newly added features
- Split Options tabs, Popup Menu tabs, and Instructions into individual Vue components
- Make various UI fixes and improvements
- Fix links routing on Options page (opening and scrolling)
- Localize Popup Menu UI

## v0.2.2

- Fix issue where right-to-left languages were not aligned to the center
- Add translation services access check to the instruction
- Temporarily fixed the error message on starting to listen on domains belonging to Meta

## v0.2.1

- Adapt to Edge Add-ons Store publication
- Add basic support for languages: Filipino, Italian, Swahili, Thai, Vietnamese, Chinese (Taiwan)

## v0.2.0

- Add the Text Outline option that changes the text appearance
- Add the Center Text option that positions the text in the center
- Add the Hide the divider lines option that removes the lines between translations
- Add preset text colors for the Overlay Mode
- Add a detached preview window for the appearance setup
- Add the Hide the interim text option that displays only the final text
- Add the Auto Hide on inactivity option for the widget for the Streaming Mode
- Add an option to customize the max number of letters per translation when Streaming Mode is turned on
- Update the Appearance, Configuration and Streaming Setup instructions
- Add instructions on how to adjust the translation chunk size and how to translate to multiple languages
- Add a new release note appearance logic that works when the store has a new minor release
- Make minor UI and UX improvements

## v0.1.1

- Add disclaimer for Android instruction

## v0.1.0

- Add Streaming Mode, that shows the translation to viewers in a widget
- Add instruction for machine-assisted translation (human real-time translation)
- Add translation display in the side panel of the browser
- Add minimalistic view for translation window on page (iframe)
- Add contribute button to support the developer
- Add support reminder notifications
- Improve UI of quick settings menu
- Fix animation appearing issue
- Refactor new text appearing code base
- Change listening state algorithm watch
- Add personal translation and streaming server functionality
- Add changelog on update functionality
- Remove system notifications option for translations
- Add instruction for Android

## v0.0.3

- Replace Chrome references with browser-neutral terms
- Rewrite Linux setup instructions
- Add an article about speech recognition services
- Add an article about standalone application usage (in Edge)
- Add an article about multiple-instances setup for interviews
- Fix standalone application icon display (in Edge)
- Fix microphone permission image for Windows (camera changed to microphone in the latest versions of Chrome)
- Fix non-working number of preserved translations setting

## v0.0.2

- Fix Streaming Setup article 7 slide displaying
- Fix font-weight for light theme
- Fix extension description

## v0.0.1

Initial release
