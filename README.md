# CamelSnakeConverter

## Features

- [x] toCamel
- [x] toSnake

## Requirements

- iOS 8.0+
- Xcode 7.3+

## Communication

- If you **need help**, use [Stack Overflow](http://stackoverflow.com).
- If you'd like to **ask a general question**, use [Stack Overflow](http://stackoverflow.com).
- If you **found a bug**, open an issue.
- If you **have a feature request**, open an issue.
- If you **want to contribute**, submit a pull request.

## Installation

### CocoaPods

[CocoaPods](http://cocoapods.org) is a dependency manager for Cocoa projects. You can install it with the following command:

```bash
$ gem install cocoapods
```

To integrate into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
platform :ios, '9.0'
use_frameworks!

target '<Your Target Name>' do
    pod 'CamelSnakeConverter', :git => 'https://github.com/bloodysnowx/CamelSnakeConverter.git'
end
```

Then, run the following command:

```bash
$ pod install
```

## Usage

```swift
import CamelSnakeConverter

"a_snake_case".toCamel()
"aCamelCase".toSnake()
```

## License

is released under the MIT license. See LICENSE for details.
