fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
### create_app
```
fastlane create_app
```
Create app on developer portal and App Store Connect if needed

----

## iOS
### ios bump
```
fastlane ios bump
```
Bump version and build number
### ios signing
```
fastlane ios signing
```
Sync signing
### ios build
```
fastlane ios build
```
Build binary
### ios release
```
fastlane ios release
```
Release binary

----

## Mac
### mac bump
```
fastlane mac bump
```
Bump version and build number
### mac signing
```
fastlane mac signing
```
Sync signing
### mac build
```
fastlane mac build
```
Build binary
### mac release
```
fastlane mac release
```
Release binary

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
