| Announcements |
|-|
| [[macOS] The macOS 12 Actions runner image will begin deprecation on 10/7/24 and will be fully unsupported by 12/3/24 for GitHub and ADO](https://github.com/actions/runner-images/issues/10721) |
| [[macOS] Support policy changes; Xcode 14 and 16 will be removed from macOS 14 on October 28](https://github.com/actions/runner-images/issues/10703) |
| [macOS 15 (Sequoia) is now available as a public beta in GitHub Actions](https://github.com/actions/runner-images/issues/10686) |
| [[Macos 13 and 14] Android NDK versions <=25 will be removed from images on October 07,2024](https://github.com/actions/runner-images/issues/10614) |
| [[Macos 13 and 14] Go version 1.20.0 will be removed on October 07,2024.](https://github.com/actions/runner-images/issues/10612) |
***
# macOS 13
- OS Version: macOS 13.7 (22H123)
- Kernel Version: Darwin 22.6.0
- Image Version: 20241008.186

## Installed Software

### Language and Runtime
- .NET Core SDK: 7.0.102, 7.0.202, 7.0.306, 7.0.410, 8.0.101, 8.0.204, 8.0.303, 8.0.403
- Bash 3.2.57(1)-release
- Clang/LLVM 14.0.0
- Clang/LLVM (Homebrew) 15.0.7 - available on `$(brew --prefix llvm@15)/bin/clang`
- GCC 12 (Homebrew GCC 12.4.0) - available by `gcc-12` alias
- GCC 13 (Homebrew GCC 13.3.0) - available by `gcc-13` alias
- GCC 14 (Homebrew GCC 14.2.0) - available by `gcc-14` alias
- GNU Fortran 12 (Homebrew GCC 12.4.0) - available by `gfortran-12` alias
- GNU Fortran 13 (Homebrew GCC 13.3.0) - available by `gfortran-13` alias
- GNU Fortran 14 (Homebrew GCC 14.2.0) - available by `gfortran-14` alias
- Kotlin 2.0.20-release-360
- Mono 6.12.0.188
- Node.js 20.18.0
- Perl 5.38.2
- PHP 8.3.12
- Python3 3.12.7
- Ruby 3.0.7p220

### Package Management
- Bundler 2.5.21
- Carthage 0.40.0
- CocoaPods 1.15.2
- Composer 2.8.1
- Homebrew 4.4.0
- NPM 10.8.2
- NuGet 6.3.1.1
- Pip3 24.2 (python 3.12)
- Pipx 1.7.1
- RubyGems 3.5.21
- Vcpkg 2024 (build from commit 2ddc10c8a)
- Yarn 1.22.22

### Project Management
- Apache Ant 1.10.15
- Apache Maven 3.9.9
- Gradle 8.10.2

### Utilities
- 7-Zip 17.05
- aria2 1.37.0
- azcopy 10.26.0
- bazel 7.3.2
- bazelisk 1.22.0
- bsdtar 3.5.3 - available by 'tar' alias
- Curl 8.10.1
- Git 2.47.0
- Git LFS 3.5.1
- GitHub CLI 2.58.0
- GNU Tar 1.35 - available by 'gtar' alias
- GNU Wget 1.24.5
- gpg (GnuPG) 2.4.5
- jq 1.7.1
- OpenSSL 1.1.1w  11 Sep 2023
- Packer 1.11.2
- pkg-config 0.29.2
- yq 4.44.3
- zstd 1.5.6

### Tools
- AWS CLI 2.18.1
- AWS SAM CLI 1.125.0
- AWS Session Manager CLI 1.2.650.0
- Azure CLI 2.65.0
- Azure CLI (azure-devops) 1.0.1
- Bicep CLI 0.30.23
- Cmake 3.30.4
- CodeQL Action Bundle 2.19.1
- Fastlane 2.224.0
- SwiftFormat 0.54.5
- Xcbeautify 2.11.0
- Xcode Command Line Tools 14.3.1.0.1.1683849156
- Xcodes 1.5.0

### Linters
- SwiftLint 0.57.0

### Browsers
- Safari 18.0.1 (18619.1.26.111.11)
- SafariDriver 18.0.1 (18619.1.26.111.11)
- Google Chrome 129.0.6668.90
- Google Chrome for Testing 129.0.6668.89
- ChromeDriver 129.0.6668.89
- Microsoft Edge 129.0.2792.79
- Microsoft Edge WebDriver 129.0.2792.82
- Mozilla Firefox 131.0
- geckodriver 0.35.0
- Selenium server 4.25.0

#### Environment variables
| Name            | Value                                 |
| --------------- | ------------------------------------- |
| CHROMEWEBDRIVER | /usr/local/share/chromedriver-mac-x64 |
| EDGEWEBDRIVER   | /usr/local/share/edge_driver          |
| GECKOWEBDRIVER  | /usr/local/opt/geckodriver/bin        |

### Java
| Version             | Environment Variable |
| ------------------- | -------------------- |
| 8.0.422+5.1         | JAVA_HOME_8_X64      |
| 11.0.24+8           | JAVA_HOME_11_X64     |
| 17.0.12+7 (default) | JAVA_HOME_17_X64     |
| 21.0.4+7.0          | JAVA_HOME_21_X64     |

### Cached Tools

#### PyPy
- 2.7.18 [PyPy 7.3.17]
- 3.7.13 [PyPy 7.3.9]
- 3.8.16 [PyPy 7.3.11]
- 3.9.19 [PyPy 7.3.16]
- 3.10.14 [PyPy 7.3.17]

#### Ruby
- 3.0.7
- 3.1.6
- 3.2.5
- 3.3.5

#### Python
- 3.8.18
- 3.9.20
- 3.10.15
- 3.11.9
- 3.12.7

#### Node.js
- 16.20.2
- 18.20.4
- 20.18.0

#### Go
- 1.21.13
- 1.22.8
- 1.23.2

### Rust Tools
- Cargo 1.81.0
- Rust 1.81.0
- Rustdoc 1.81.0
- Rustup 1.27.1

#### Packages
- Clippy 0.1.81
- Rustfmt 1.7.1-stable

### PowerShell Tools
- PowerShell 7.4.5

#### PowerShell Modules
- Az: 12.4.0
- Pester: 5.6.1
- PSScriptAnalyzer: 1.22.0

### Xcode
| Version        | Build   | Path                           |
| -------------- | ------- | ------------------------------ |
| 15.2 (default) | 15C500b | /Applications/Xcode_15.2.app   |
| 15.1           | 15C65   | /Applications/Xcode_15.1.app   |
| 15.0.1         | 15A507  | /Applications/Xcode_15.0.1.app |
| 14.3.1         | 14E300c | /Applications/Xcode_14.3.1.app |
| 14.2           | 14C18   | /Applications/Xcode_14.2.app   |
| 14.1           | 14B47b  | /Applications/Xcode_14.1.app   |

#### Installed SDKs
| SDK                                                     | SDK Name                                      | Xcode Version |
| ------------------------------------------------------- | --------------------------------------------- | ------------- |
| macOS 13.0                                              | macosx13.0                                    | 14.1          |
| macOS 13.1                                              | macosx13.1                                    | 14.2          |
| macOS 13.3                                              | macosx13.3                                    | 14.3.1        |
| macOS 14.0                                              | macosx14.0                                    | 15.0.1        |
| macOS 14.2                                              | macosx14.2                                    | 15.1, 15.2    |
| iOS 16.1                                                | iphoneos16.1                                  | 14.1          |
| iOS 16.2                                                | iphoneos16.2                                  | 14.2          |
| iOS 16.4                                                | iphoneos16.4                                  | 14.3.1        |
| iOS 17.0                                                | iphoneos17.0                                  | 15.0.1        |
| iOS 17.2                                                | iphoneos17.2                                  | 15.1, 15.2    |
| Simulator - iOS 16.1                                    | iphonesimulator16.1                           | 14.1          |
| Simulator - iOS 16.2                                    | iphonesimulator16.2                           | 14.2          |
| Simulator - iOS 16.4                                    | iphonesimulator16.4                           | 14.3.1        |
| Simulator - iOS 17.0                                    | iphonesimulator17.0                           | 15.0.1        |
| Simulator - iOS 17.2                                    | iphonesimulator17.2                           | 15.1, 15.2    |
| tvOS 16.1                                               | appletvos16.1                                 | 14.1, 14.2    |
| tvOS 16.4                                               | appletvos16.4                                 | 14.3.1        |
| tvOS 17.0                                               | appletvos17.0                                 | 15.0.1        |
| tvOS 17.2                                               | appletvos17.2                                 | 15.1, 15.2    |
| Simulator - tvOS 16.1                                   | appletvsimulator16.1                          | 14.1, 14.2    |
| Simulator - tvOS 16.4                                   | appletvsimulator16.4                          | 14.3.1        |
| Simulator - tvOS 17.0                                   | appletvsimulator17.0                          | 15.0.1        |
| Simulator - tvOS 17.2                                   | appletvsimulator17.2                          | 15.1, 15.2    |
| watchOS 9.1                                             | watchos9.1                                    | 14.1, 14.2    |
| watchOS 9.4                                             | watchos9.4                                    | 14.3.1        |
| watchOS 10.0                                            | watchos10.0                                   | 15.0.1        |
| watchOS 10.2                                            | watchos10.2                                   | 15.1, 15.2    |
| Simulator - watchOS 9.1                                 | watchsimulator9.1                             | 14.1, 14.2    |
| Simulator - watchOS 9.4                                 | watchsimulator9.4                             | 14.3.1        |
| Simulator - watchOS 10.0                                | watchsimulator10.0                            | 15.0.1        |
| Simulator - watchOS 10.2                                | watchsimulator10.2                            | 15.1, 15.2    |
| visionOS 1.0                                            | xros1.0                                       | 15.2          |
| Simulator - visionOS 1.0                                | xrsimulator1.0                                | 15.2          |
| Asset Runtime SDK for macOS hosts targeting watchOS 9.4 | assetruntime.host.macosx.target.watchos9.4    | 14.3.1        |
| Asset Runtime SDK for macOS hosts targeting tvOS 16.4   | assetruntime.host.macosx.target.appletvos16.4 | 14.3.1        |
| Asset Runtime SDK for macOS hosts targeting iOS 16.4    | assetruntime.host.macosx.target.iphoneos16.4  | 14.3.1        |
| DriverKit 22.1                                          | driverkit22.1                                 | 14.1          |
| DriverKit 22.2                                          | driverkit22.2                                 | 14.2          |
| DriverKit 22.4                                          | driverkit22.4                                 | 14.3.1        |
| DriverKit 23.0                                          | driverkit23.0                                 | 15.0.1        |
| DriverKit 23.2                                          | driverkit23.2                                 | 15.1, 15.2    |

#### Installed Simulators
| OS           | Simulators                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| iOS 16.1     | iPhone 14<br>iPhone 14 Plus<br>iPhone 14 Pro<br>iPhone 14 Pro Max<br>iPhone SE (3rd generation)<br>iPad (10th generation)<br>iPad Air (5th generation)<br>iPad mini (6th generation)<br>iPad Pro (11-inch) (4th generation)<br>iPad Pro (12.9-inch) (6th generation)                                                                                                                                                                                             |
| iOS 16.2     | iPhone 14<br>iPhone 14 Plus<br>iPhone 14 Pro<br>iPhone 14 Pro Max<br>iPhone SE (3rd generation)<br>iPad (10th generation)<br>iPad Air (5th generation)<br>iPad mini (6th generation)<br>iPad Pro (11-inch) (4th generation)<br>iPad Pro (12.9-inch) (6th generation)                                                                                                                                                                                             |
| iOS 16.4     | iPhone 14<br>iPhone 14 Plus<br>iPhone 14 Pro<br>iPhone 14 Pro Max<br>iPhone SE (3rd generation)<br>iPad (10th generation)<br>iPad Air (5th generation)<br>iPad mini (6th generation)<br>iPad Pro (11-inch) (4th generation)<br>iPad Pro (12.9-inch) (6th generation)                                                                                                                                                                                             |
| iOS 17.0     | iPhone 14<br>iPhone 14 Plus<br>iPhone 14 Pro<br>iPhone 14 Pro Max<br>iPhone 15<br>iPhone 15 Plus<br>iPhone 15 Pro<br>iPhone 15 Pro Max<br>iPhone SE (3rd generation)<br>iPad (10th generation)<br>iPad Air (5th generation)<br>iPad mini (6th generation)<br>iPad Pro (11-inch) (4th generation)<br>iPad Pro (12.9-inch) (6th generation)                                                                                                                        |
| iOS 17.2     | iPhone 14<br>iPhone 14 Plus<br>iPhone 14 Pro<br>iPhone 14 Pro Max<br>iPhone 15<br>iPhone 15 Plus<br>iPhone 15 Pro<br>iPhone 15 Pro Max<br>iPhone SE (3rd generation)<br>iPad (10th generation)<br>iPad Air (5th generation)<br>iPad mini (6th generation)<br>iPad Pro (11-inch) (4th generation)<br>iPad Pro (12.9-inch) (6th generation)                                                                                                                        |
| tvOS 16.1    | Apple TV<br>Apple TV 4K (3rd generation)<br>Apple TV 4K (3rd generation) (at 1080p)                                                                                                                                                                                                                                                                                                                                                                              |
| tvOS 16.4    | Apple TV<br>Apple TV 4K (3rd generation)<br>Apple TV 4K (3rd generation) (at 1080p)                                                                                                                                                                                                                                                                                                                                                                              |
| tvOS 17.0    | Apple TV<br>Apple TV 4K (3rd generation)<br>Apple TV 4K (3rd generation) (at 1080p)                                                                                                                                                                                                                                                                                                                                                                              |
| tvOS 17.2    | Apple TV<br>Apple TV 4K (3rd generation)<br>Apple TV 4K (3rd generation) (at 1080p)                                                                                                                                                                                                                                                                                                                                                                              |
| watchOS 9.1  | Apple Watch SE (40mm) (2nd generation)<br>Apple Watch SE (44mm) (2nd generation)<br>Apple Watch Series 5 (40mm)<br>Apple Watch Series 5 (44mm)<br>Apple Watch Series 6 (40mm)<br>Apple Watch Series 6 (44mm)<br>Apple Watch Series 7 (41mm)<br>Apple Watch Series 7 (45mm)<br>Apple Watch Series 8 (41mm)<br>Apple Watch Series 8 (45mm)<br>Apple Watch Ultra (49mm)                                                                                             |
| watchOS 9.4  | Apple Watch SE (40mm) (2nd generation)<br>Apple Watch SE (44mm) (2nd generation)<br>Apple Watch Series 5 (40mm)<br>Apple Watch Series 5 (44mm)<br>Apple Watch Series 6 (40mm)<br>Apple Watch Series 6 (44mm)<br>Apple Watch Series 7 (41mm)<br>Apple Watch Series 7 (45mm)<br>Apple Watch Series 8 (41mm)<br>Apple Watch Series 8 (45mm)<br>Apple Watch Ultra (49mm)                                                                                             |
| watchOS 10.0 | Apple Watch SE (40mm) (2nd generation)<br>Apple Watch SE (44mm) (2nd generation)<br>Apple Watch Series 5 (40mm)<br>Apple Watch Series 5 (44mm)<br>Apple Watch Series 6 (40mm)<br>Apple Watch Series 6 (44mm)<br>Apple Watch Series 7 (41mm)<br>Apple Watch Series 7 (45mm)<br>Apple Watch Series 8 (41mm)<br>Apple Watch Series 8 (45mm)<br>Apple Watch Series 9 (41mm)<br>Apple Watch Series 9 (45mm)<br>Apple Watch Ultra (49mm)<br>Apple Watch Ultra 2 (49mm) |
| watchOS 10.2 | Apple Watch SE (40mm) (2nd generation)<br>Apple Watch SE (44mm) (2nd generation)<br>Apple Watch Series 5 (40mm)<br>Apple Watch Series 5 (44mm)<br>Apple Watch Series 6 (40mm)<br>Apple Watch Series 6 (44mm)<br>Apple Watch Series 7 (41mm)<br>Apple Watch Series 7 (45mm)<br>Apple Watch Series 8 (41mm)<br>Apple Watch Series 8 (45mm)<br>Apple Watch Series 9 (41mm)<br>Apple Watch Series 9 (45mm)<br>Apple Watch Ultra (49mm)<br>Apple Watch Ultra 2 (49mm) |

### Android
| Package Name               | Version                                                                                                                                                                                                                             |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Android Command Line Tools | 11.0                                                                                                                                                                                                                                |
| Android Emulator           | 35.2.10                                                                                                                                                                                                                             |
| Android SDK Build-tools    | 35.0.0<br>34.0.0<br>33.0.2 33.0.3                                                                                                                                                                                                   |
| Android SDK Platforms      | android-35 (rev 1)<br>android-34-ext8 (rev 1)<br>android-34-ext12 (rev 1)<br>android-34-ext11 (rev 1)<br>android-34-ext10 (rev 1)<br>android-34 (rev 3)<br>android-33-ext5 (rev 1)<br>android-33-ext4 (rev 1)<br>android-33 (rev 3) |
| Android SDK Platform-Tools | 35.0.2                                                                                                                                                                                                                              |
| Android Support Repository | 47.0.0                                                                                                                                                                                                                              |
| CMake                      | 3.22.1                                                                                                                                                                                                                              |
| Google Play services       | 49                                                                                                                                                                                                                                  |
| Google Repository          | 58                                                                                                                                                                                                                                  |
| NDK                        | 26.3.11579264 (default)<br>27.1.12297006                                                                                                                                                                                            |

#### Environment variables
| Name                    | Value                                               |
| ----------------------- | --------------------------------------------------- |
| ANDROID_HOME            | /Users/runner/Library/Android/sdk                   |
| ANDROID_NDK             | /Users/runner/Library/Android/sdk/ndk/26.3.11579264 |
| ANDROID_NDK_HOME        | /Users/runner/Library/Android/sdk/ndk/26.3.11579264 |
| ANDROID_NDK_LATEST_HOME | /Users/runner/Library/Android/sdk/ndk/27.1.12297006 |
| ANDROID_NDK_ROOT        | /Users/runner/Library/Android/sdk/ndk/26.3.11579264 |
| ANDROID_SDK_ROOT        | /Users/runner/Library/Android/sdk                   |

### Miscellaneous
- Tcl/Tk 8.6.15

#### Environment variables
| Name              | Value                                                                                     |
| ----------------- | ----------------------------------------------------------------------------------------- |
| PARALLELS_DMG_URL | https://download.parallels.com/desktop/v20/20.1.0-55732/ParallelsDesktop-20.1.0-55732.dmg |

##### Notes
```
If you want to use Parallels Desktop you should download a package from URL stored in
PARALLELS_DMG_URL environment variable. A system extension is allowed for this version.
```

