# SDWebImageWebPCoder

[![CI Status](http://img.shields.io/travis/SDWebImage/SDWebImageWebPCoder.svg?style=flat)](https://travis-ci.org/SDWebImage/SDWebImageWebPCoder)
[![Version](https://img.shields.io/cocoapods/v/SDWebImageWebPCoder.svg?style=flat)](http://cocoapods.org/pods/SDWebImageWebPCoder)
[![License](https://img.shields.io/cocoapods/l/SDWebImageWebPCoder.svg?style=flat)](http://cocoapods.org/pods/SDWebImageWebPCoder)
[![Platform](https://img.shields.io/cocoapods/p/SDWebImageWebPCoder.svg?style=flat)](http://cocoapods.org/pods/SDWebImageWebPCoder)
[![SwiftPM compatible](https://img.shields.io/badge/SwiftPM-compatible-brightgreen.svg?style=flat)](https://swift.org/package-manager/)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/SDWebImage/SDWebImageWebPCoder)
[![codecov](https://codecov.io/gh/SDWebImage/SDWebImageWebPCoder/branch/master/graph/badge.svg)](https://codecov.io/gh/SDWebImage/SDWebImageWebPCoder)

Starting with the SDWebImage 5.0 version, we moved the WebP support code and [libwebp](https://github.com/webmproject/libwebp) from the Core Repo to this stand-alone repo.

SDWebImageWebPCoder supports both WebP decoding and encoding, for Static WebP or Animated WebP as well.

Note: Apple's ImageIO supports WebP decoding from iOS 14/tvOS 14/watchOS 7/macOS 11, so SDWebImage on those platform can also decode WebP images (using `SDWebImageAWebPCoder` built-in coder). However it may contains some limitation, check https://github.com/SDWebImage/SDWebImage/issues/3558, you can still force to use this coder on those platforms by adding this coder.

## Requirements

+ iOS 9.0
+ macOS 10.11
+ tvOS 9.0
+ watchOS 2.0
+ Xcode 11.0

## Installation

#### CocoaPods

SDWebImageWebPCoder is available through [CocoaPods](http://cocoapods.org). To install it, simply add the following line to your Podfile:

```ruby
pod 'SDWebImageWebPCoder'
```

#### Carthage

SDWebImageWebPCoder is available through [Carthage](https://github.com/Carthage/Carthage).

```
github "SDWebImage/SDWebImageWebPCoder"
```

#### Swift Package Manager (Xcode 11+)

SDWebImageWebPCoder is available through [Swift Package Manager](https://swift.org/package-manager).

```swift
let package = Package(
    dependencies: [
        .package(url: "https://github.com/SDWebImage/SDWebImageWebPCoder.git", from: "0.3.0")
    ]
)
```

## Usage
