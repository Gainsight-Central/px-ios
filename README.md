[![N|Solid](https://app-dev.aptrinsic.com/home/gainsight-px-logo.svg)](https://app.aptrinsic.com)

![version](https://img.shields.io/badge/version-2-blue.svg)

# Installation

## Swift Package Manager

```swift
dependencies: [
    .package(url: "https://github.com/Gainsight-Central/px-ios.git", from: "2.0.2")
]
```

## CocoaPods

The framework is now available on CocoaPods directly.

Add pod `Gainsight-PX` to the Podfile as follows:

```rb
target 'MyApp' do
    pod 'Gainsight-PX'
end
```

Run a `pod install` from your terminal, or from CocoaPods.app.
> **IMPORTANT**: Ensure that the framework that you have integrated earlier is removed before proceeding with the installation.

You can also still use the previous method of installing the framework from GitHub:

```rb
pod 'PXKit', :git => 'git@github.com:Gainsight-Central/px-ios.git', tag: '2.0.2'
```

> or

```rb
pod 'PXKit', :git => 'git@github.com:Gainsight-Central/px-ios.git'
```

# Documentation

More detailed documentation is available at: <https://support.gainsight.com/PX/Mobile/Getting_Started/03Integrate_Gainsight_PX_with_iOS>

## Editor Deeplinking

More detailed documentation is available at: <https://support.gainsight.com/PX/Mobile/01Getting_Started/Integrate_Gainsight_PX_Editor_with_your_Mobile_Platform>

# Release Notes

See [CHANGELOG.md](CHANGELOG.md).

# License

MIT License. See [LICENSE](LICENSE).
