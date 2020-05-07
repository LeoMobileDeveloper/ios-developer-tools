## Contents

- [Website](#website)
- [IDE](#ide)
- [Dependency Manager](#dependency-manager)
- [Platform](#platform)
- [Command Line Tool](#command-line-tool)
- [DEBUG](#debug)
- [Project Analyze](#project-analyze)
- [Network](#network)
- [Data](#data) 
- [Compiler](#compiler)
- [Test](#test)
- [Localization](#localization)
- [Reverse engineering](#reverse-engineering)
- [App Guard](#app-guard)
- [Chrome Extension](#chrome)
- [Other](#other)


## Website

- [stackoverflow](https://stackoverflow.com/) Stack Overflow is a question and answer site for professional and enthusiast programmers.
- [Apple Developer Forums](https://developer.apple.com/devforums/) The Apple Developer Forums are a great place to post questions and share comments with fellow developers and Apple engineers. 
- [objc.io](https://www.objc.io/) objc.io publishes books, videos, and articles on advanced techniques for iOS and macOS development.
- [nshipster](https://nshipster.com/) NSHipster is a journal of the overlooked bits in Objective-C, Swift, and Cocoa. Updated weekly.
- [raywenderlich](https://www.raywenderlich.com/ios/) Learn iOS development in Swift.
- [medium](https://medium.com/ios-os-x-development) Stories and technical tips about building apps for iOS, Apple Watch, and iPad/iPhone
- [Best-websites-a-programmer-should-visit](https://github.com/sdmg15/Best-websites-a-programmer-should-visit) 🔗 Some useful websites for programmers.

### Apple

- [WWDC](https://developer.apple.com/wwdc/)
- [Apple Open Source](https://opensource.apple.com/tarballs)
- [App Store Promote](https://developer.apple.com//contact/app-store/promote/)
- [Expedited App Review](https://developer.apple.com/contact/app-store/)
- [Apple Design Resources](https://developer.apple.com/design/resources/)
- [Optimizing for App Store Search](https://developer.apple.com/app-store/search/)
- [Apple System Status](https://developer.apple.com/system-status/) 
- [App Store Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)
    - [Simplified Chinese](https://developer.apple.com/cn/app-store/review/guidelines/)
- [Auto-renewable Subscriptions](https://developer.apple.com/app-store/subscriptions/)

## IDE

- [Xcode](https://developer.apple.com/xcode/) you will spend most of your time with it 
    - [awesome-xcode-extensions](https://github.com/theswiftdev/awesome-xcode-extensions) Awesome native Xcode extensions.
    - [iOS-DeviceSupport](https://github.com/iGhibli/iOS-DeviceSupport) This repository holds the device support files for the iOS, and I will update it regularly.
    - [iOS-DeviceSupport](https://github.com/iGhibli/iOS-DeviceSupport/tree/master/DeviceSupport) This repository holds the device support files for the iOS, and I will update it regularly.
- [Atom](https://atom.io/) + [Nuclide](https://nuclide.io/) If you need to write react-native Code
- [MacDown](http://macdown.uranusjr.com/) open source Markdown editor for macOS
- [Visual Studio Code](https://code.visualstudio.com/) Visual Studio Code is a source code editor. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring.
- [starUML](http://staruml.io/) A sophisticated software modeler for agile and concise modeling

## Dependency Manager

- [CocoaPods](http://cocoapods.org/) dependency manager for Swift and Objective-C Cocoa projects
    - [cocoapods-dependencies](https://github.com/segiddins/cocoapods-dependencies) Shows a project's CocoaPods dependency graph
    - [cocoapods-amimono](https://github.com/Ruenzuo/cocoapods-amimono) Move all dynamic frameworks symbols into the main executable.
    - [cocoapods-packager](https://github.com/CocoaPods/cocoapods-packager) CocoaPods plugin which allows you to generate a static library from a podspec.
    - [cocoapods-static-swift-framework](https://github.com/leavez/cocoapods-static-swift-framework) A cocoapods plugin enables static framework for all pods
- [Carthage](https://github.com/Carthage/Carthage) A simple, decentralized dependency manager for Cocoa
- [Accio](https://github.com/JamitLabs/Accio) A dependency manager driven by SwiftPM that works for iOS/tvOS/watchOS/macOS projects.

## Platform

- [Firebase](https://firebase.google.com/) Firebase is a BaaS  (Backend-as-a-Service) that can be your server, datastore, and API at the same time. 
	- [Crashlytics](https://firebase.google.com/docs/crashlytics/) Spend less time troubleshooting & more time building great apps. 
- [Parse](https://parseplatform.org/) Build applications faster with object and file storage,
user authentication, push notifications, dashboard and more out of the box.


## Command Line Tool

- [xcodebuild](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/xcodebuild.1.html) and - [xcrun](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/xcrun.1.html) command line tool to build and archive app
- [xctool](https://github.com/facebook/xctool) An extension for Apple's xcodebuild that makes it easier to test iOS and macOS apps.
- [idb](https://github.com/facebook/idb) idb is a flexible command line interface for automating iOS simulators and devices
- [xcbuild](https://github.com/facebook/xcbuild) xcbuild is an Xcode-compatible build tool with the goal of providing faster builds, better documentation of the build process and running on multiple platforms (macOS, Linux, and Windows)
- [synx](https://github.com/venmo/synx) A command-line tool that reorganizes your Xcode project folder to match your Xcode groups
- [Kin](https://github.com/Karumi/Kin) Simple PBXProj Verifier (If you has problem to git merge the project.pbxproj file)
- [tmux](https://github.com/tmux/tmux) tmux is a "terminal multiplexer", it enables a number of terminals (or windows)
to be accessed and controlled from a single terminal.
- [iTerm2](https://www.iterm2.com/) iTerm2 is a replacement for Terminal and the successor to iTerm. It works on Macs with macOS 10.10 or newer. iTerm2 brings the terminal into the modern age with features you never knew you always wanted.
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/) A delightful community-driven (with 1,300+ contributors) framework for managing your zsh configuration. 
- [xcpretty](https://github.com/supermarin/xcpretty) Flexible and fast xcodebuild formatter
- [Jazzy](https://github.com/realm/jazzy) Soulful docs for Swift & Objective-C 
- [xiblint](https://github.com/lyft/xiblint) A tool for linting storyboard and xib files
- [brew](https://github.com/Homebrew/brew) 🍺 The missing package manager for macOS
- [cloc](https://github.com/AlDanial/cloc) cloc counts blank lines, comment lines, and physical lines of source code in many programming languages.
- [xcproj](https://github.com/0xced/xcproj) Command line tool for manipulating Xcode project files
- [autojump](https://github.com/wting/autojump) A cd command that learns - easily navigate directories from the command line
- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) A code library and command-line formatting tool for reformatting Swift code
- [SwiftRewriter](https://github.com/inamiy/SwiftRewriter) 📝 Swift code formatter using SwiftSyntax.
- objdump llvm object file dumper
- [XcodeGen](https://github.com/yonaskolb/XcodeGen) A Swift command line tool for generating your Xcode project
- [plutil](https://www.theiphonewiki.com/wiki/Plutil) plutil is a program that can convert .plist files between a binary version and an XML version. Currently, there are two versions of this utility.
- [dsymutil](https://llvm.org/docs/CommandGuide/dsymutil.html) dsymutil links the DWARF debug information found in the object files for an executable executable by using debug symbols information contained in its symbol table. 
- [symboliccrash](https://developer.apple.com/library/archive/technotes/tn2151/_index.html) Symbolicating crash reports
- [ArgumentParser](https://swift.org/blog/argument-parser/) Open-source library that makes it straightforward to parse command-line arguments in Swift

## DEBUG

- [Instruments](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/index.html) Instruments is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. 
    - [gtm_load_timer](https://github.com/google/gtm_load_timer) A framework and instrument for timing Objective C +load messages.
    - [speedscope](https://github.com/jlfwong/speedscope) Flame graphs of Time Profiler
- [DBDebugToolkit](https://github.com/dbukowski/DBDebugToolkit) Set of easy to use debugging tools for iOS developers & QA engineers.
- [Flipper](https://fbsonar.com/) Flipper is a platform for debugging mobile apps on iOS and Android. Visualize, inspect, and control your apps from a simple desktop interface. Use Flipper as is or extend it using the plugin API.
- [chisel](https://github.com/facebook/chisel) Chisel is a collection of LLDB commands to assist debugging iOS apps.
- [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) A fast & simple, yet powerful & flexible logging framework for Mac and iOS
- [PonyDebugger](https://github.com/square/PonyDebugger)Remote network and data debugging for your native iOS app using Chrome Developer Tools
- [dSYMTools](https://github.com/answer-huang/dSYMTools) Analyze crash log with DSYM file
- [Hexspeak](https://en.m.wikipedia.org/wiki/Hexspeak) Table about exception code in crash log 
- [FLEX](https://github.com/Flipboard/FLEX) An in-app debugging and exploration tool for iOS
- [MTHawkeye](https://github.com/meitu/MTHawkeye) Profiling / Debugging assist tools for iOS.
- [GodEye](https://github.com/zixun/GodEye) Automaticly display Log,Crash,Network,ANR,Leak,CPU,RAM,FPS,NetFlow,Folder and etc with one line of code based on Swift. Just like God opened his eyes
- [injectionforxcode](https://github.com/johnno1962/injectionforxcode) Injection for Xcode is an Xcode plugin (available via Alcatraz) or AppCode that dynamically inserts new Swift / Objective-C code into a running app in order to speed up your build process
- [WBWebViewConsole](https://github.com/Naituw/WBWebViewConsole) In-App debug console for your UIWebView & WKWebView
- [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy) A DevTools proxy (Chrome Remote Debugging Protocol) for iOS devices (Safari Remote Web Inspector).
- [spy-debugger](https://github.com/wuchangming/spy-debugger) WebView,WeChat WebView,Safari Debugger
- [AppleTrace](https://github.com/everettjf/AppleTrace) Objective C message tracing tool for iOS/macOS
- [iOS Console](http://lemonjar.com/iosconsole/) iOS Console allows you to view iOS console logs directly from your Mac
- [iSimulator](https://github.com/wigl/iSimulator) iSimulator is a GUI utility to control the Simulator, and manage the app installed on the simulator.
- [DoraemonKit](https://github.com/didi/DoraemonKit) A full-featured App (iOS & Android) development assistant.
- [NWPusher](https://github.com/noodlewerk/NWPusher) OS X and iOS application and framework to play with the Apple Push Notification service (APNs)
- [Knuff](https://github.com/KnuffApp/Knuff) The debug application for Apple Push Notification Service (APNs).
- [matrix](https://github.com/Tencent/matrix) Matrix is a plugin style, non-invasive APM system developed by WeChat.
- [Hexspeak](https://en.m.wikipedia.org/wiki/Hexspeak) termination code detail in crash log 
- [PLCrashReporter](https://www.plcrashreporter.org/) Reliable, open-source crash reporting for iOS and Mac OS X.
- [KSCrash](https://github.com/kstenerud/KSCrash) The Ultimate iOS Crash Reporter
- [InAppViewDebugger](https://github.com/indragiek/InAppViewDebugger) A UIView debugger (like Reveal or Xcode) that can be embedded in an app for on-device view debugging
- [Hyperion](https://github.com/willowtreeapps/Hyperion-iOS) In-app design review tool to inspect measurements, attributes, and animations.
- [LookinServer](https://github.com/QMUI/LookinServer) Free macOS app for iOS view debugging
- [LayoutInspector](https://github.com/isavynskyi/LayoutInspector) Tool to debug layouts directly on iOS devices: inspect layers in 3D and debug each visible view attributes
- [XCLogParser](https://github.com/spotify/XCLogParser) Tool to parse the SLF serialization format used by Xcode and xcodebuild to store its Build and Test logs (xcactivitylog).
- [beyond compare](https://www.scootersoftware.com/download.php) Compare files and folders using simple, powerful commands that focus on the differences you're interested in and ignore those you're not.  Merge changes, synchronize files, and generate reports.
- [restore-symbol](https://github.com/tobefuturer/restore-symbol) A reverse engineering tool to restore stripped symbol table for iOS app.

### Memory 

- [FBRetainCycleDetector](https://github.com/facebook/FBRetainCycleDetector) iOS library to help detecting retain cycles in runtime.
- [FBMemoryProfiler](https://github.com/facebook/FBMemoryProfiler) iOS tool that helps with profiling iOS Memory usage.
- [FBAllocationTracker](https://github.com/facebook/FBAllocationTracker) iOS library that helps tracking all allocated Objective-C objects
- [OOMDetector](https://github.com/Tencent/OOMDetector) OOMDetector is a memory monitoring component for iOS which provides you with OOM monitoring, memory allocation monitoring, memory leak detection and other functions.
- [LifetimeTracker](https://github.com/krzysztofzablocki/LifetimeTracker) Find retain cycles / memory leaks sooner

## Project Analyze

- [oclint](http://oclint.org/) Static code analysis tool for improving quality and reducing defects by inspecting C, C++ and Objective-C code and looking for potential problems.
- [swiftlint](https://github.com/realm/SwiftLint) A tool to enforce Swift style and conventions. 
- [objc-dependency-visualizer](https://github.com/PaulTaykalo/objc-dependency-visualizer) Objective-C and Swift dependency visualizer. It's tool that helps to visualize current state of your project. It's really easy to see how tight your classes are coupled.
- [LSUnusedResources](https://github.com/tinymind) A Mac App to find unused images and resources in XCode project.
- [WHC_ScanUnreferenceImageTool](https://github.com/netyouli/WHC_ScanUnreferenceImageTool) Scanning project does not use images in tool, delete without reference images to reduce the packaging volume
- [FengNiao](https://github.com/onevcat/FengNiao) A command line tool for cleaning unused resources in Xcode.
- [IBAnalyzer](https://github.com/fastred/IBAnalyzer) Find common xib and storyboard-related problems without running your app or writing unit tests.
- [Simian](http://www.harukizaemon.com/simian/index.html) Similarity Analyser
- [cartool](https://github.com/steventroughtonsmith/cartool) Export images from OS X / iOS .car CoreUI archives
- [XcodeZombieCode](https://github.com/kangwang1988/XcodeZombieCode) A source-code level/Clang Approach
- [Faux Pas](http://fauxpasapp.com/) Find errors in your iOS or Mac project(Not free)
- [xcodeproj](https://github.com/tuist/xcodeproj) 📝 Read, update and write your Xcode projects https://tuist.github.io/xcodeproj/
- [objc_dep](https://github.com/nst/objc_dep) Graph the import dependencies in an Objective-C project
- [AssetCatalogTinkerer](https://github.com/insidegui/AssetCatalogTinkerer) An app that lets you open .car files and browse/extract their images.
- [periphery](https://github.com/peripheryapp/periphery) Eliminate Unused Swift Code.
- [fui](https://github.com/dblock/fui) Find unused Objective-C imports.
- [objc_cover](https://github.com/nst/objc_cover) Quick Python script over otool to help spotting potentially unused methods in Objective-C Mach-O executable files
- [Pecker](https://github.com/woshiccm/Pecker.git) A tool to detect unused Swift code based on [IndexStoreDB](https://github.com/apple/indexstore-db.git) and [SwiftSyntax](https://github.com/apple/swift-syntax.git).

## Network

- [Charles](https://www.charlesproxy.com/) Charles is an HTTP proxy / HTTP monitor / Reverse Proxy that enables a developer to view all of the HTTP and SSL / HTTPS traffic between their machine and the Internet.
- [Proxyman](https://proxyman.io) Proxyman 👨‍🚀 is a high-performance macOS app, which enables developers to view HTTP/HTTPS requests from apps and domains. Support iOS Simulator and iOS devices. Easy to use and user friendly.
- [Postman](https://www.getpostman.com/) Faster, easier API development 
- [iperf](https://github.com/esnet/iperf) iperf3: A TCP, UDP, and SCTP network bandwidth measurement tool
- [Lantern](https://github.com/getlantern/lantern) Lantern delivers fast access to the open Internet
- [shadowsocks](https://shadowsocks.org/en/index.html) A secure socks5 proxy,designed to protect your Internet traffic.
- [wireshark](https://www.wireshark.org/) Wireshark is the world’s foremost and widely-used network protocol analyzer. It lets you see what’s happening on your network at a microscopic level and is the de facto (and often de jure) standard across many commercial and non-profit enterprises, government agencies, and educational institutions.
- [netfox](https://github.com/kasketis/netfox) A lightweight, one line setup, iOS / OSX network debugging library! 🦊
- [GCDWebServer](https://github.com/swisspol/GCDWebServer) GCDWebServer is a modern and lightweight GCD based HTTP 1.1 server designed to be embedded in iOS, macOS & tvOS apps.
- [JSONLint](https://jsonlint.com/) JSONLint is a validator and reformatter for JSON, a lightweight data-interchange format
- [Wormholy](https://github.com/pmusolino/Wormholy) iOS network debugging

## Data

- [sqlitebrowser](http://sqlitebrowser.org/) DB Browser for SQLite
- [TablePlus](https://tableplus.com/) Modern, native GUI client for SQLite
- [SimPholders](https://simpholders.com/) Access all applications from your menu bar,and quick open Sandbox of Simulator
- [SimSim](https://github.com/dsmelov/simsim) Fast, stable, free alternative to SimPholders
- [SQLCipher](https://github.com/sqlcipher/sqlcipher) SQLCipher is an SQLite extension that provides 256 bit AES encryption of database files

## Compiler

- [ccache](https://ccache.samba.org/) ccache is a compiler cache. It speeds up recompilation by caching previous compilations and detecting when the same compilation is being done again
- [swiff](https://github.com/agens-no/swiff) Human readable time diffs on lines of output when running e.g. build commands like fastlane
- [ClangKit](https://github.com/macmade/ClangKit) ClangKit provides an Objective-C frontend to LibClang. Source tokenization, diagnostics and fix-its are actually implemented.
- [Optimizing-Swift-Build-Times](https://github.com/fastred/Optimizing-Swift-Build-Times) Collection of advice on optimizing compile times of Swift projects.
- [Ninja](https://ninja-build.org/) Ninja is a small build system with a focus on speed
- [emscripten](https://github.com/kripken/emscripten) An LLVM-to-JavaScript Compiler
- [antlr4](https://github.com/antlr/antlr4) ANTLR (ANother Tool for Language Recognition) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. http://antlr.org
- [BuildTimeAnalyzer-for-Xcode](https://github.com/RobertGummesson/BuildTimeAnalyzer-for-Xcode) Build Time Analyzer for Swift
- [SourceKitten](https://github.com/jpsim/SourceKitten) An adorable little framework and command line tool for interacting with SourceKit.
- [zld](https://github.com/michaeleisel/zld) A faster version of Apple's linker
- [xcconfigs](https://github.com/xcconfigs/xcconfigs) Common Xcode configuration files/settings.

## Test

- [TestFlight](https://developer.apple.com/testflight/) TestFlight makes it easy to invite users to test your apps and collect valuable feedback before releasing your apps on the App Store. 
- [appium](http://appium.io/) Appium is an open source test automation framework for use with native, hybrid and mobile web apps. It drives iOS, Android, and Windows apps using the WebDriver protocol.
- [FBSnapshotTestCase](https://github.com/facebookarchive/ios-snapshot-test-case) Snapshot view unit tests for iOS
- [Kiwi](https://github.com/kiwi-bdd/Kiwi) Simple BDD for iOS
- [Quick](https://github.com/Quick/Quick) The Swift (and Objective-C) testing framework.
- [OCMock](https://github.com/erikdoe/ocmock) Mock objects for Objective-C
- [KIF](https://github.com/kif-framework/KIF) Keep It Functional - An iOS Functional Testing Framework
- [Specta](https://github.com/specta/specta) A light-weight TDD / BDD framework for Objective-C.
- [EarlGrey](https://github.com/google/EarlGrey) 🍵 iOS UI Automation Test Framework 
- [SwiftMonkey](https://github.com/zalando/SwiftMonkey) A framework for doing randomised UI testing of iOS apps
- [swift-snapshot-testing](https://github.com/pointfreeco/swift-snapshot-testing) 📸 Delightful Swift snapshot testing
- [XcodeCoverage](https://github.com/jonreid/XcodeCoverage) Code coverage for Xcode projects (Objective-C only)
- [ios-deploy](https://github.com/ios-control/ios-deploy) Install and debug iPhone apps from the command line, without using Xcode
- [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) A cross-platform protocol library to communicate with iOS devices
- [usbmuxd](https://github.com/libimobiledevice/usbmuxd) A socket daemon to multiplex connections from and to iOS devices
- [ios-snapshot-test-case](https://github.com/uber/ios-snapshot-test-case) Snapshot view unit tests for iOS

## Localization

- [Loca Studio](https://www.cunningo.com/locastudio/index.html) Analyze, review, and edit your app translations. Can directly open the Xcode Localization Catalog (xcloc) and XLIFF 1.2 file formats.

## Reverse engineering

- [IPSW](https://ipsw.me/) Download current and previous versions of Apple's iOS Firmware and receive notifications when new firmwares are released.
- [canijailbreak](https://canijailbreak.com/) jailbreak tools
- [ios-app-signer](https://github.com/DanTheMan827/ios-app-signer) This is an app for OS X that can (re)sign apps and bundle them into ipa files that are ready to be installed on an iOS device.
- [MonkeyDev](https://github.com/AloneMonkey/MonkeyDev) CaptainHook Tweak、Logos Tweak and Command-line Tool、Patch iOS Apps, Without Jailbreak.
- [class dump](http://stevenygard.com/projects/class-dump/) a command-line utility for examining the Objective-C runtime information stored in Mach-O files
- [Keychain-Dumper](https://github.com/ptoomey3/Keychain-Dumper)A tool to check which keychain items are available to an attacker once an iOS device has been jailbroken
- [reveal](https://revealapp.com/) Reveal brings powerful runtime view debugging to iOS developers
- [theos](https://github.com/theos/theos) Unified cross-platform Makefile system
- [iPhoneDevWiki](http://iphonedevwiki.net/index.php/Main_Page) Wiki about jailbroken iOS development
- [Hopper Disassembler](https://www.hopperapp.com/) Reverse engineering tool that lets you disassemble, decompile and debug your applications. 
- [MachOView](https://github.com/gdbinit/MachOView) View the raw data of mach-o(iOS executable file format)
- [ruby-macho](https://github.com/Homebrew/ruby-macho) 🔩 A pure-Ruby library for parsing Mach-O files.
- [frida](https://www.frida.re/) Dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers.
- [cycript](http://www.cycript.org/) Cycript allows developers to explore and modify running applications on either iOS or Mac OS X using a hybrid of Objective-C++ and JavaScript syntax through an interactive console that features syntax highlighting and tab completion.
- [dumpdecrypted](https://github.com/stefanesser/dumpdecrypted) Dumps decrypted mach-o files from encrypted iPhone applications from memory to disk. This tool is necessary for security researchers to be able to look under the hood of encryption.
- [passionfruit](https://github.com/chaitin/passionfruit) Simple iOS app blackbox assessment tool. Powered by frida.re and vuejs.
- [objection](https://github.com/sensepost/objection) Assess mobile applications and their security posture without the need for a jailbroken or rooted mobile device.
- [Hikari](https://github.com/HikariObfuscator/Hikari) LLVM Obfuscator https://keybase.io/team/hikari
- [Clutch](https://github.com/KJCracks/Clutch) Fast iOS executable dumper
- [otool](https://www.unix.com/man-page/osx/1/otool/) The otool command displays specified parts of object files or libraries. It can also disassemble:
- [xxd](https://ss64.com/osx/xxd.html) xxd creates a hex dump of a given file or standard input. It can also convert a hex dump back to its original binary form
- [nm](http://unixhelp.ed.ac.uk/CGI/man-cgi?nm) nm is a utility that displays the symbol table of a given binary.
- [jtool](http://www.newosxbook.com/tools/jtool.html) The jtool command is meant to meet and exceed the functionality to XCode's otool(1), picking up along the way additional Mach-O commands such as atos(1), dyldinfo(1), nm(1), segedit(1), pagestuff(1), strings(1) , and even codesign(1) and the informal ldid. 
- [capstone](https://github.com/aquynh/capstone) Capstone disassembly/disassembler framework
- [class-dump-swift](https://github.com/Maximus-/class-dump-swift) Swift Class Dumper
- [iosre](http://bbs.iosre.com/) Chinese reverse engineering bbs
- [Retriever](https://github.com/cyanzhong/Retriever) Retrieving InfoPlist without Jailbreaking on iOS Devices
- [iOS-Runtime-Headers](https://github.com/nst/iOS-Runtime-Headers) iOS Objective-C headers as derived from runtime introspection
- [http://developer.limneos.net](http://developer.limneos.net) Website to browse iOS runtime headers
- [iReSign](https://github.com/maciekish/iReSign) iReSign allows iDevice app bundles (.ipa) files to be signed or resigned with a digital certificate from Apple for distribution.
- [MachO-Kit](https://github.com/DeVaukz/MachO-Kit) A C/Objective-C library for parsing Mach-O files.
- [insert_dylib](https://github.com/Tyilo/insert_dylib) Command line utility for inserting a dylib load command into a Mach-O binary
- [yololib](https://github.com/KJCracks/yololib) dylib injector for mach-o binaries
- [dyld_cache_extract](https://github.com/macmade/dyld_cache_extract) A macOS utility to extract dynamic libraries from the dyld_shared_cache of macOS and iOS
- [app2dylib](https://github.com/tobefuturer/app2dylib) A reverse engineering tool to convert iOS app to dylib
- [apple configuration2](https://apps.apple.com/cn/app/apple-configurator-2/id1037126344?l=en&mt=12) Download ipa file from App Store
- [iphonecake.com](http://www.iphonecake.com) Cracked iOS & Mac App Store
- [optool](https://github.com/alexzielenski/optool) optool is a tool which interfaces with MachO binaries in order to insert/remove load commands, strip code signatures, resign, and remove aslr. Below is its help.
- [Macholib](https://macholib.readthedocs.io/en/latest/) macholib can be used to analyze and edit Mach-O headers, the executable format used by Mac OS X.
- [fishhook](https://github.com/facebook/fishhook) A library that enables dynamically rebinding symbols in Mach-O binaries running on iOS. You can use fishhook to hook C function.
- [iOS-System-Symbols](https://github.com/Zuikyo/iOS-System-Symbols) Share iOS system framework's symbol files. Useful for symbolicating iOS crash report.
- [Synalyze It](https://www.synalysis.net/) Synalyze It! allows you to create a “grammar“ for your binary files interactively. Unlike in regular hex editors or viewers the files are interpreted automatically for you! Analysis of binary files has never been easier.

## App Guard

- [ios-class-guard](https://github.com/Polidea/ios-class-guard) Simple Objective-C obfuscator for Mach-O executables
- [obfuscator](https://github.com/obfuscator-llvm/obfuscator) obfuscator
- [Obfuscator-iOS](https://github.com/pjebs/Obfuscator-iOS) Secure your app by obfuscating all the hard-coded security-sensitive strings.
- [swiftshield](https://github.com/rockbruno/swiftshield) Swift Obfuscator that protects iOS apps against reverse engineering attacks.
- [MachObfuscator](https://github.com/kam800/MachObfuscator) MachObfuscator is a programming-language-agnostic Mach-O apps obfuscator for Apple platforms.

## Image

- [cwebp](https://developers.google.com/speed/webp/docs/cwebp) Compress an image file to a WebP file
- [ImageOptim](https://imageoptim.com/mac) ImageOptim makes images load faster
- [TinyPng.com](https://tinypng.com/) Smart PNG and JPEG compression
- [Speculid](https://github.com/brightdigit/Speculid) Easily Manage Graphics in Xcode Projects https://speculid.com

## Chrome

- [The Great Suspender](https://chrome.google.com/webstore/detail/the-great-suspender/klbibkeccnjlkjkiokjodocebajanakg) Make your computer run smoothly by suspending the tabs you aren't using

## Other

- [UTM](https://github.com/utmapp/UTM) Virtual machines for iOS
- [Alfred](https://www.alfredapp.com/) Alfred is an award-winning app for macOS which boosts your efficiency with hotkeys, keywords, text expansion and more. 
- [Bear](https://bear.app/) Bear is a beautiful, flexible writing app for crafting notes and prose.
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
- [Haiku](https://www.haiku.ai/) Design components that snap into any codebase
- [Sketch](https://www.sketchapp.com/) Sketch gives you the power, flexibility and speed you always wanted in a lightweight and easy-to-use package. Finally you can focus on what you do best: Design.
- [Dribbble](https://dribbble.com/) Dribbble is the leading destination to find & showcase creative work and home to the world's best design professionals
- [gif brewery](http://gifbrewery.com/) Easy to create GIF
- [jazzy](https://github.com/realm/jazzy) Soulful docs for Swift & Objective-C
- [lottie-ios](https://github.com/airbnb/lottie-ios) An iOS library to natively render After Effects vector animations 
- [public-apis](https://github.com/toddmotto/public-apis) A collective list of public JSON APIs。
- [Smartmockups](https://smartmockups.com/) Free product mockup generator
- [flaticon](https://www.flaticon.com/) 1,695,000 vector icons grouped in 35,450 packs
- [Semaphore CI for iOS](https://semaphoreci.com/product/ios) Semaphore is the fastest way to test and deploy iOS apps.
- [ios app maximum memory budget](https://stackoverflow.com/questions/5887248/ios-app-maximum-memory-budget/15200855#15200855) ios app maximum memory budget
- [draw.io](https://draw.io) draw.io is free online diagram software for making flowcharts, process diagrams, org charts, UML, ER and network diagrams.
- [PushMate](https://pushmate.app) PushMate is a MacOS app that solves common push notification problems by ensuring your push payloads are correct.
- [emojipedia](https://emojipedia.org) Wiki of emoji
- [XcodeCleaner](https://github.com/waylybaye/XcodeCleaner) Cleaner for Xcode.app built with react-native-macos
- [SkrybaMD](https://github.com/robertherdzik/SkrybaMD) - Markdown Documentation generator. If your team need easy way to maintain and create documentation, this generator is for you.
- [Swiftify](https://swiftify.com/#/converter/code/) - Objective-C to Swift Converter
- [Storyboard -> SwiftUI Converter](https://swiftify.com/#/converter/storyboard2swiftui/) - Storyboard / Xib to SwiftUI converter
