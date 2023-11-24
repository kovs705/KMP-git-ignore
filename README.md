# KMP-git-ignore

git ignore template for KMP project overall
```
*.iml
*.gradle
/local.properties
.idea
.DS_Store
/build
/captures
.externalNativeBuild
local.properties
.cxx
local.properties
/multiplatformLibrary/build/
/*/build/
**/build/
/androidlk/build/
/multiplatformLibrary/build/
```

git ignore template for iOS part (swiftpm,swift,cocoapods,carthage,fastlane,objective-c)
⚠️ Warning: this .gitignore file exclude .xcodeproj so you need to use XCodeGen to generate project from .yml file
```
### Carthage ###
# Carthage
#
# Add this line if you want to avoid checking in source code from Carthage dependencies.
# Carthage/Checkouts

Carthage/Build

### fastlane ###

# fastlane specific
**/fastlane/report.xml

# deliver temporary files
**/fastlane/Preview.html

# snapshot generated screenshots
**/fastlane/screenshots

# scan temporary files
**/fastlane/test_output

# Fastlane.swift runner binary
**/fastlane/FastlaneRunner

### Objective-C ###
# Xcode

## User settings
xcuserdata/

## compatibility with Xcode 8 and earlier
*.xcscmblueprint
*.xccheckout

## compatibility with Xcode 3 and earlier
build/
DerivedData/
*.moved-aside
*.pbxuser
!default.pbxuser
*.mode1v3
!default.mode1v3
*.mode2v3
!default.mode2v3
*.perspectivev3
!default.perspectivev3

## Obj-C/Swift specific
*.hmap

## App packaging
*.ipa
*.dSYM.zip
*.dSYM

### CocoaPods ###
Pods/
*.xcworkspace

# Carthage
Carthage/Checkouts

Carthage/Build/

# fastlane

fastlane/report.xml
fastlane/Preview.html
fastlane/screenshots/**/*.png
fastlane/test_output

# Code Injection
# After new code Injection tools there's a generated folder /iOSInjectionProject

iOSInjectionProject/

### Objective-C Patch ###

### Swift ###
# Xcode

## Playgrounds
timeline.xctimeline
playground.xcworkspace

# Swift Package Manager
Packages/
Package.pins
Package.resolved
*.xcodeproj
.swiftpm

.build/

# CocoaPods
# We recommend against adding the Pods directory to your .gitignore. However
# you should judge for yourself, the pros and cons are mentioned at:
# https://guides.cocoapods.org/using/using-cocoapods.html#should-i-check-the-pods-directory-into-source-control
# Pods/
# Add this line if you want to avoid checking in source code from the Xcode workspace
# *.xcworkspace

# Carthage
# Add this line if you want to avoid checking in source code from Carthage dependencies.
# Carthage/Checkouts


# Accio dependency management
Dependencies/
.accio/

# fastlane
# It is recommended to not store the screenshots in the git repo.
# Instead, use fastlane to re-generate the screenshots whenever they are needed.
# For more information about the recommended setup visit:
# https://docs.fastlane.tools/best-practices/source-control/#source-control


# Code Injection
# After new code Injection tools there's a generated folder /iOSInjectionProject
# https://github.com/johnno1962/injectionforxcode


### SwiftPM ###
Packages
xcuserdata
*.xcodeproj

# CSV
*.orig
.svn

*.xcodeproj/*
!*.xcodeproj/project.pbxproj
!*.xcworkspace/contents.xcworkspacedata

# Other
*~
.DS_Store
*.swp
*.save
._*
*.bak
```
