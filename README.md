# awesome-ios-develop-tools
A list of tools such like Charles that are helpful during developing iOS App

## IDE
- [XCode](https://developer.apple.com/xcode/) you will spend most of your time in it 
- [CocoaPods](http://cocoapods.org/) dependency manager for Swift and Objective-C Cocoa projects
- [Carthage](https://github.com/Carthage/Carthage) A simple, decentralized dependency manager for Cocoa
- [Atom](https://atom.io/) + [Nuclide](https://nuclide.io/) If you need to write react-native Code
- [MacDown](http://macdown.uranusjr.com/) open source Markdown editor for macOS
- [Visual Studio Code](https://code.visualstudio.com/) Excellent ide

## Command Line Tool
- [xcodebuild](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/xcodebuild.1.html) and - [xcrun](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/xcrun.1.html) command line tool to build and archive app
- [xctool](https://github.com/facebook/xctool) An extension for Apple's xcodebuild that makes it easier to test iOS and macOS apps.
- [synx](https://github.com/venmo/synx) A command-line tool that reorganizes your Xcode project folder to match your Xcode groups
- [Kin](https://github.com/Karumi/Kin) Simple PBXProj Verifier (If you has problem to git merge the project.pbxproj file)
tmux is a "terminal multiplexer", it enables a number of terminals (or windows)
to be accessed and controlled from a single terminal.
- [tmux](https://github.com/tmux/tmux) tmux is a "terminal multiplexer", it enables a number of terminals (or windows)
to be accessed and controlled from a single terminal.

## DEBUG
- [chisel](https://github.com/facebook/chisel) Chisel is a collection of LLDB commands to assist debugging iOS apps.
- [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) A fast & simple, yet powerful & flexible logging framework for Mac and iOS
- [PonyDebugger](https://github.com/square/PonyDebugger)Remote network and data debugging for your native iOS app using Chrome Developer Tools
- [dSYMTools](https://github.com/answer-huang/dSYMTools) Anaylize crash log with DSYM file
- [FBRetainCycleDetector](https://github.com/facebook/FBRetainCycleDetector/tree/master/FBRetainCycleDetector) iOS library to help detecting retain cycles in runtime.
- [FLEX](https://github.com/Flipboard/FLEX) An in-app debugging and exploration tool for iOS
- [GodEye](https://github.com/zixun/GodEye) Automaticly display Log,Crash,Network,ANR,Leak,CPU,RAM,FPS,NetFlow,Folder and etc with one line of code based on Swift. Just like God opened his eyes
- [injectionforxcode](https://github.com/johnno1962/injectionforxcode) Injection for Xcode is an Xcode plugin (available via Alcatraz) or AppCode that dynamically inserts new Swift / Objective-C code into a running app in order to speed up your build process

## Project Anaylize
- [oclint](http://oclint.org/) Static code analysis tool for improving quality and reducing defects by inspecting C, C++ and Objective-C code and looking for potential problems.
- [swiftlint](https://github.com/realm/SwiftLint) A tool to enforce Swift style and conventions. 
- [objc-dependency-visualizer](https://github.com/PaulTaykalo/objc-dependency-visualizer) Objective-C and Swift dependency visualizer. It's tool that helps to visualize current state of your project. It's really easy to see how tight your classes are coupled.
- [WHC_ScanUnreferenceImageTool](https://github.com/netyouli/WHC_ScanUnreferenceImageTool) Scanning project does not use images in tool, delete without reference images to reduce the packaging volume


## Network
- [Charles](https://www.charlesproxy.com/) Charles is an HTTP proxy / HTTP monitor / Reverse Proxy that enables a developer to view all of the HTTP and SSL / HTTPS traffic between their machine and the Internet.
- [Postman](https://www.getpostman.com/) Faster, easier API development 
- [Lantern](https://github.com/getlantern/lantern) Lantern delivers fast access to the open Internet （翻墙）
- [wireshark](https://www.wireshark.org/) Wireshark is the world’s foremost and widely-used network protocol analyzer. It lets you see what’s happening on your network at a microscopic level and is the de facto (and often de jure) standard across many commercial and non-profit enterprises, government agencies, and educational institutions.

## Data
- [sqlitebrowser](http://sqlitebrowser.org/) DB Browser for SQLite
- [SimPholders](https://simpholders.com/)Access all applications from your menu bar,and quick open Sandbox of Simulator

## Other
- [Jenkins](https://jenkins.io/index.html) Continuous integration (CI)
- [fastlane](https://github.com/fastlane/fastlane) Automate building and releasing your iOS and Android apps 
- [appledoc](http://gentlebytes.com/appledoc/) Objective-C API documentation generator 
- [Source Tree](http://www.sourcetreeapp.com/) Harness the power of Git and Hg in a beautifully simple application
- [PaintCode](https://www.paintcodeapp.com/) Turn drawings into code.
- [reflector](http://www.airsquirrels.com/reflector/) wireless mirroring and streaming receiver 
- [Sketch](https://www.sketchapp.com/) Sketch gives you the power, flexibility and speed you always wanted in a lightweight and easy-to-use package. Finally you can focus on what you do best: Design.
- [gif brewery](http://gifbrewery.com/) Easy to create GIF
- [NWPusher](https://github.com/noodlewerk/NWPusher) OS X and iOS application and framework to play with the Apple Push Notification service (APNs)
- [jazzy](https://github.com/realm/jazzy) Soulful docs for Swift & Objective-C
- [ImageOptim](https://imageoptim.com/mac) ImageOptim makes images load faster
- [TinyPng.com](https://tinypng.com/) Smart PNG and JPEG compression


## Reverse engineering

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

