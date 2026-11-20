STAR TVOS - PROJECT RESET PACKAGE

This is a clean Android project source package for GitHub Actions builds.
It is not an APK yet. GitHub Actions builds the APK after the source files
are uploaded to the repository.

Included:
- Android TV launcher activity
- D-pad focus and OK/click actions
- Launch intents for Netflix, YouTube, Prime Video and Disney+ (if installed)
- TV Settings shortcut
- Android package visibility declarations
- HOME / DEFAULT intent categories so Android TV can offer it as a home launcher
- GitHub Actions workflow to build app-debug.apk

Important:
1. The app can only open streaming apps that are installed and expose a launch activity.
2. Some TV brands use different package IDs or app variants.
3. Background is an animated gradient, not movie posters or video backgrounds yet.
4. After installing, select STAR TVOS as the Home app/default launcher if the TV offers that choice.

Project files should be placed at the repository root with the same paths as in this ZIP.
