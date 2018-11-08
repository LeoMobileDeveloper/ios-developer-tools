# ios-developer-tools

A collection of tools that an iOS developer should know.

## IDE

- [XCode](https://developer.apple.com/xcode/) you will spend most of your time in it 
- [CocoaPods](http://cocoapods.org/) dependency manager for Swift and Objective-C Cocoa projects
- [Carthage](https://github.com/Carthage/Carthage) A simple, decentralized dependency manager for Cocoa
- [Atom](https://atom.io/) + [Nuclide](https://nuclide.io/) If you need to write react-native Code
- [MacDown](http://macdown.uranusjr.com/) open source Markdown editor for macOS
- [Visual Studio Code](https://code.visualstudio.com/) Excellent ide
- [starUML](http://staruml.io/) A sophisticated software modeler for agile and concise modeling

## Command Line Tool

- [xcodebuild](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/xcodebuild.1.html) and - [xcrun](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/xcrun.1.html) command line tool to build and archive app
- [xctool](https://github.com/facebook/xctool) An extension for Apple's xcodebuild that makes it easier to test iOS and macOS apps.
- [xcbuild](https://github.com/facebook/xcbuild) xcbuild is an Xcode-compatible build tool with the goal of providing faster builds, better documentation of the build process and running on multiple platforms (macOS, Linux, and Windows)
- [synx](https://github.com/venmo/synx) A command-line tool that reorganizes your Xcode project folder to match your Xcode groups
- [Kin](https://github.com/Karumi/Kin) Simple PBXProj Verifier (If you has problem to git merge the project.pbxproj file)
tmux is a "terminal multiplexer", it enables a number of terminals (or windows)
to be accessed and controlled from a single terminal.
- [tmux](https://github.com/tmux/tmux) tmux is a "terminal multiplexer", it enables a number of terminals (or windows)
to be accessed and controlled from a single terminal.
- [iTerm2](https://www.iterm2.com/) iTerm2 is a replacement for Terminal and the successor to iTerm. It works on Macs with macOS 10.10 or newer. iTerm2 brings the terminal into the modern age with features you never knew you always wanted.
- [xcpretty](https://github.com/supermarin/xcpretty) Flexible and fast xcodebuild formatter
- [Jazzy](https://github.com/realm/jazzy) Soulful docs for Swift & Objective-C 
- [xiblint](https://github.com/lyft/xiblint) A tool for linting storyboard and xib files
- [brew](https://github.com/Homebrew/brew) 🍺 The missing package manager for macOS
- [cloc](https://github.com/AlDanial/cloc) cloc counts blank lines, comment lines, and physical lines of source code in many programming languages.

## DEBUG

- [Sonar](https://fbsonar.com/) Sonar is a platform for debugging mobile apps on iOS and Android. Visualize, inspect, and control your apps from a simple desktop interface. Use Sonar as is or extend it using the plugin API.
- [chisel](https://github.com/facebook/chisel) Chisel is a collection of LLDB commands to assist debugging iOS apps.
- [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) A fast & simple, yet powerful & flexible logging framework for Mac and iOS
- [PonyDebugger](https://github.com/square/PonyDebugger)Remote network and data debugging for your native iOS app using Chrome Developer Tools
- [dSYMTools](https://github.com/answer-huang/dSYMTools) Anaylize crash log with DSYM file
- [FBRetainCycleDetector](https://github.com/facebook/FBRetainCycleDetector/tree/master/FBRetainCycleDetector) iOS library to help detecting retain cycles in runtime.
- [FLEX](https://github.com/Flipboard/FLEX) An in-app debugging and exploration tool for iOS
- [GodEye](https://github.com/zixun/GodEye) Automaticly display Log,Crash,Network,ANR,Leak,CPU,RAM,FPS,NetFlow,Folder and etc with one line of code based on Swift. Just like God opened his eyes
- [injectionforxcode](https://github.com/johnno1962/injectionforxcode) Injection for Xcode is an Xcode plugin (available via Alcatraz) or AppCode that dynamically inserts new Swift / Objective-C code into a running app in order to speed up your build process
- [Instruments](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/index.html) Instruments is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. 
- [WBWebViewConsole](https://github.com/Naituw/WBWebViewConsole) In-App debug console for your UIWebView & WKWebView
- [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy) A DevTools proxy (Chrome Remote Debugging Protocol) for iOS devices (Safari Remote Web Inspector).
- [spy-debugger](https://github.com/wuchangming/spy-debugger) WebView,WeChat WebView,Safari Debugger
- [Apple System Status](https://developer.apple.com/system-status/) 

## Project Anaylize

- [oclint](http://oclint.org/) Static code analysis tool for improving quality and reducing defects by inspecting C, C++ and Objective-C code and looking for potential problems.
- [swiftlint](https://github.com/realm/SwiftLint) A tool to enforce Swift style and conventions. 
- [objc-dependency-visualizer](https://github.com/PaulTaykalo/objc-dependency-visualizer) Objective-C and Swift dependency visualizer. It's tool that helps to visualize current state of your project. It's really easy to see how tight your classes are coupled.
- [WHC_ScanUnreferenceImageTool](https://github.com/netyouli/WHC_ScanUnreferenceImageTool) Scanning project does not use images in tool, delete without reference images to reduce the packaging volume
- [FengNiao](https://github.com/onevcat/FengNiao) A command line tool for cleaning unused resources in Xcode.
- [IBAnalyzer](https://github.com/fastred/IBAnalyzer) Find common xib and storyboard-related problems without running your app or writing unit tests.
- [Simian](http://www.harukizaemon.com/simian/index.html) Similarity Analyser
- [cartool](https://github.com/steventroughtonsmith/cartool) Export images from OS X / iOS .car CoreUI archives
- [XcodeZombieCode](https://github.com/kangwang1988/XcodeZombieCode) A source-code level/Clang Approach
- [Faux Pas](http://fauxpasapp.com/) Find errors in your iOS or Mac project(Not free)
- [xcodeproj](https://github.com/tuist/xcodeproj) 📝 Read, update and write your Xcode projects https://tuist.github.io/xcodeproj/
- [AssetCatalogTinkerer](https://github.com/insidegui/AssetCatalogTinkerer) An app that lets you open .car files and browse/extract their images.

## Network

- [Charles](https://www.charlesproxy.com/) Charles is an HTTP proxy / HTTP monitor / Reverse Proxy that enables a developer to view all of the HTTP and SSL / HTTPS traffic between their machine and the Internet.
- [Postman](https://www.getpostman.com/) Faster, easier API development 
- [Lantern](https://github.com/getlantern/lantern) Lantern delivers fast access to the open Internet
- [shadowsocks](https://shadowsocks.org/en/index.html) A secure socks5 proxy,designed to protect your Internet traffic.
- [wireshark](https://www.wireshark.org/) Wireshark is the world’s foremost and widely-used network protocol analyzer. It lets you see what’s happening on your network at a microscopic level and is the de facto (and often de jure) standard across many commercial and non-profit enterprises, government agencies, and educational institutions.
- [netfox](https://github.com/kasketis/netfox) A lightweight, one line setup, iOS / OSX network debugging library! 🦊
- [JSONLint](https://jsonlint.com/) JSONLint is a validator and reformatter for JSON, a lightweight data-interchange format

## Data

- [sqlitebrowser](http://sqlitebrowser.org/) DB Browser for SQLite
- [SimPholders](https://simpholders.com/)Access all applications from your menu bar,and quick open Sandbox of Simulator

## Compiler

- [ccache](https://ccache.samba.org/) ccache is a compiler cache. It speeds up recompilation by caching previous compilations and detecting when the same compilation is being done again
- [swiff](https://github.com/agens-no/swiff) Human readable time diffs on lines of output when running e.g. build commands like fastlane
- [Optimizing-Swift-Build-Times](https://github.com/fastred/Optimizing-Swift-Build-Times) Collection of advice on optimizing compile times of Swift projects.

## Apple

- [App Store Promote](https://developer.apple.com//contact/app-store/promote/)
- [Expedited App Review](https://developer.apple.com/contact/app-store/)
- [Apple Design Resources](https://developer.apple.com/design/resources/)

## Other

- [Jenkins](https://jenkins.io/index.html) Continuous integration (CI)
- [GitLabCI](https://about.gitlab.com/features/gitlab-ci-cd/) CI in gitlab
- [danger](https://github.com/danger/danger) Formalize your Pull Request etiquette.
- [fastlane](https://github.com/fastlane/fastlane) Automate building and releasing your iOS and Android apps 
- [appledoc](http://gentlebytes.com/appledoc/) Objective-C API documentation generator 
- [Source Tree](http://www.sourcetreeapp.com/) Harness the power of Git and Hg in a beautifully simple application
- [gitkraken](https://www.gitkraken.com/) The legendary Git GUI client for Windows, Mac and Linux
- [PaintCode](https://www.paintcodeapp.com/) Turn drawings into code.
- [reflector](http://www.airsquirrels.com/reflector/) wireless mirroring and streaming receiver 
- [Sketch](https://www.sketchapp.com/) Sketch gives you the power, flexibility and speed you always wanted in a lightweight and easy-to-use package. Finally you can focus on what you do best: Design.
- [gif brewery](http://gifbrewery.com/) Easy to create GIF
- [NWPusher](https://github.com/noodlewerk/NWPusher) OS X and iOS application and framework to play with the Apple Push Notification service (APNs)
- [jazzy](https://github.com/realm/jazzy) Soulful docs for Swift & Objective-C
- [ImageOptim](https://imageoptim.com/mac) ImageOptim makes images load faster
- [TinyPng.com](https://tinypng.com/) Smart PNG and JPEG compression
- [OOMDetector](https://github.com/Tencent/OOMDetector) OOMDetector is a memory monitoring component for iOS which provides you with OOM monitoring, memory allocation monitoring, memory leak detection and other functions.
- [lottie-ios](https://github.com/airbnb/lottie-ios) An iOS library to natively render After Effects vector animations 

## Reverse engineering

- [canijailbreak](https://canijailbreak.com/) jailbreak tools
- [ios-app-signer](https://github.com/DanTheMan827/ios-app-signer) This is an app for OS X that can (re)sign apps and bundle them into ipa files that are ready to be installed on an iOS device.
- [MonkeyDev](https://github.com/AloneMonkey/MonkeyDev) CaptainHook Tweak、Logos Tweak and Command-line Tool、Patch iOS Apps, Without Jailbreak.
- [class dump](http://stevenygard.com/projects/class-dump/) a command-line utility for examining the Objective-C runtime information stored in Mach-O files
- [Keychain-Dumper](https://github.com/ptoomey3/Keychain-Dumper)A tool to check which keychain items are available to an attacker once an iOS device has been jailbroken
- [reveal](https://revealapp.com/) Reveal brings powerful runtime view debugging to iOS developers
- [theos](https://github.com/theos/theos) Unified cross-platform Makefile system
- [iPhoneDevWiki](http://iphonedevwiki.net/index.php/Main_Page) Wiki about jailbroken iOS development
- [Hopper Disassembler](https://www.hopperapp.com/) Reverse engineering tool that lets you disassemble, decompile and debug your applications. 
- [MachOView](https://github.com/gdbinit/MachOView) View the raw data of mach-o(iOS executeable file format)
- [frida](https://www.frida.re/) Dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers.
- [cycript](http://www.cycript.org/) Cycript allows developers to explore and modify running applications on either iOS or Mac OS X using a hybrid of Objective-C++ and JavaScript syntax through an interactive console that features syntax highlighting and tab completion.
- [dumpdecrypted](https://github.com/stefanesser/dumpdecrypted) Dumps decrypted mach-o files from encrypted iPhone applications from memory to disk. This tool is necessary for security researchers to be able to look under the hood of encryption.
- [passionfruit](https://github.com/chaitin/passionfruit) Simple iOS app blackbox assessment tool. Powered by frida.re and vuejs.
- [objection](https://github.com/sensepost/objection) 📱 objection - runtime mobile exploration
- [Hikari](https://github.com/HikariObfuscator/Hikari) LLVM Obfuscator https://keybase.io/team/hikari
- [Clutch](https://github.com/KJCracks/Clutch) Fast iOS executable dumper
- [otool](https://www.unix.com/man-page/osx/1/otool/) The otool command displays specified parts of object files or libraries. It can also disassemble:
- [nm](http://unixhelp.ed.ac.uk/CGI/man-cgi?nm) nm is a utility that displays the symbol table of a given binary.
- [jtool](http://www.newosxbook.com/tools/jtool.html) The jtool command is meant to meet and exceed the functionality to XCode's otool(1), picking up along the way additional Mach-O commands such as atos(1), dyldinfo(1), nm(1), segedit(1), pagestuff(1), strings(1) , and even codesign(1) and the informal ldid. 
- [capstone](https://github.com/aquynh/capstone) Capstone disassembly/disassembler framework
- [class-dump-swift](https://github.com/Maximus-/class-dump-swift) Swift Class Dumper
- [iosre](http://bbs.iosre.com/) Chinese reverse engineering bbs

## App Guard

- [ios-class-guard](https://github.com/Polidea/ios-class-guard) Simple Objective-C obfuscator for Mach-O executables
- [obfuscator](https://github.com/obfuscator-llvm/obfuscator) obfuscator
- [Obfuscator-iOS](https://github.com/pjebs/Obfuscator-iOS) Secure your app by obfuscating all the hard-coded security-sensitive strings.
- [swiftshield](https://github.com/rockbruno/swiftshield) Swift Obfuscator that protects iOS apps against reverse engineering attacks.
