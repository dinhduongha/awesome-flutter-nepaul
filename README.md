# Awesome Flutter

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![](https://img.shields.io/badge/dependencies-zero-green)
[![Last Commits](https://img.shields.io/github/last-commit/nepaul/awesome-flutter?logo=git&logoColor=white)](https://github.com/nepaul/awesome-flutter/commits/master)
[![Pull Requests](https://img.shields.io/github/issues-pr/nepaul/awesome-flutter?logo=github&logoColor=white)](https://github.com/nepaul/awesome-flutter/pulls)
[![Code size](https://img.shields.io/github/languages/code-size/nepaul/awesome-flutter?logo=github&logoColor=white)](https://github.com/nepaul/awesome-flutter)

All you should know about Flutter development!

A curated list of awesome Flutter libraries, tools, tutorials, articles and more..

**Show some ❤️ and star the repo to support the project**

# Table of Contents

- [Awesome Flutter](#awesome-flutter)
- [Table of Contents](#table-of-contents)
  - [Document](#document)
  - [Style Guide](#style-guide)
  - [Starter Samples](#starter-samples)
  - [Add Flutter to existing app](#add-flutter-to-existing-app)
  - [Navigation & Routing](#navigation--routing)
  - [Data & Backend](#data--backend)
    - [Storage](#storage)
    - [State management](#state-management)
    - [Network](#network)
  - [Components](#components)
    - [UI Kits](#ui-kits)
    - [Color](#color)
    - [Text](#text)
    - [Icon](#icon)
    - [Toast & Loading & Refresh](#toast--loading--refresh)
    - [Dialog & Alert](#dialog--alert)
    - [Popup](#popup)
    - [Picker](#picker)
    - [Bar](#bar)
    - [Chart](#chart)
    - [Switch](#switch)
    - [Swipe & Slide & Indicator](#swipe--slide--indicator)
    - [Badges & Labels](#badges--labels)
    - [Datetime](#datetime)
    - [Calendars](#calendars)
    - [Clippers](#clippers)
    - [Images](#images)
    - [List & Grid](#list--grid)
    - [Form](#form)
    - [Steps & Timelines](#steps--timelines)
    - [Progress](#progress)
    - [Editor](#editor)
    - [Effect](#effect)
  - [Plugins](#plugins)
  - [Utils](#utils)
  - [Games](#games)
  - [CI/CD](#cicd)
  - [Monitor](#monitor)
  - [Tools](#tools)
  - [Apps](#apps)
  - [Contribution](#contribution)
  - [License](#license)

## Document

- ![](https://img.shields.io/github/stars/londonappbrewery/Flutter-Course-Resources?style=social)[Flutter-Course-Resources](https://github.com/londonappbrewery/Flutter-Course-Resources)
- ![](https://img.shields.io/github/stars/olexale/flutter_roadmap?style=social) [Flutter Roadmap](https://github.com/olexale/flutter_roadmap)
- ![](https://img.shields.io/github/stars/mkobuolys/flutter-design-patterns?style=social) [flutter-design-patterns](https://github.com/mkobuolys/flutter-design-patterns) - An open-source design patterns application built with Dart and Flutter.
- ![](https://img.shields.io/github/stars/VB10/flutter-architecture-template?style=social) [flutter-architecture-template](https://github.com/VB10/flutter-architecture-template) - This project craeeted for proffesionel application arhitecture.

## Style Guide

**Lint**

- [import_sorter](https://github.com/fluttercommunity/import_sorter) -  🎯 Dart package to automatically organize your dart imports. Any dart project supported! Will sorts imports alphabetically and then group them in the following order:

  1. Dart imports
  2. Flutter imports
  3. Package imports
  4. Project imports

## Starter Samples

- ![](https://img.shields.io/github/stars/alibaba/flutter-go?style=social) [FlutterGo](https://github.com/alibaba/flutter-go)
- ![](https://img.shields.io/github/stars/iampawan/FlutterExampleApps?style=social) [FlutterExampleApps](https://github.com/iampawan/FlutterExampleApps) - Example APPS Basic Flutter apps, for flutter devs.
- ![](https://img.shields.io/github/stars/flutter/samples?style=social) 🥰 [Flutter Official Samples](https://github.com/flutter/samples) -  A collection of open source samples that illustrate best practices for Flutter.
- ![](https://img.shields.io/github/stars/brianegan/flutter_architecture_samples?style=social)[flutter_architecture_samples](https://github.com/brianegan/flutter_architecture_samples) -  TodoMVC for Flutter <http://fluttersamples.com/>
- ![](https://img.shields.io/github/stars/Sky24n/flutter_wanandroid?style=social) [flutter_wanandroid](https://github.com/Sky24n/flutter_wanandroid)
- ![](https://img.shields.io/github/stars/FilledStacks/flutter-tutorials?style=social)[flutter-tutorials](https://github.com/FilledStacks/flutter-tutorials) -  The repo contains the source code for all the tutorials on the FilledStacks Youtube channel.
- ![](https://img.shields.io/github/stars/flutter/gallery?style=social) [Flutter Gallery](https://github.com/flutter/gallery) s a resource to help developers evaluate and use Flutter. It is a collection of Material Design & Cupertino widgets, behaviors, and vignettes implemented with Flutter. We often get asked how one can see Flutter in action, and this gallery demonstrates what Flutter provides and how it behaves in the wild.
- ![](https://img.shields.io/github/stars/diegoveloper/flutter-samples?style=social) [flutter-samples](https://github.com/diegoveloper/flutter-samples)
- ![](https://img.shields.io/github/stars/syncfusion/flutter-examples?style=social) [syncfusion/flutter-examples](https://github.com/syncfusion/flutter-examples) - This repository contains awesome demos of Syncfusion Flutter UI widgets. This is the best place to check our widgets to get more insight into the usage of APIs. You can also check our widgets by installing the complete Flutter sample browser from Google Play Store or App Store, in which you can browse the demo for all the widgets and view the source code of each sample within the app itself.

- ![](https://img.shields.io/github/stars/bdlukaa/fluent_ui?style=social) [fluent_ui](https://github.com/bdlukaa/fluent_ui) - Unofficial implementation of Fluent UI for Flutter. It's written based on the official documentation

- ![](https://img.shields.io/github/stars/google/flutter.widgets?style=social) 💗[google/flutter.widgets](https://github.com/google/flutter.widgets) - This repository contains the source code for various Flutter widgets that are developed by Google but not by the core Flutter team.
  - [visibility_detector](https://github.com/google/flutter.widgets/blob/master/packages/visibility_detector/README.md)
  - [self_storing_input](https://github.com/google/flutter.widgets/blob/master/packages/self_storing_input/README.md) - A set of input widgets that automatically save and load the entered value to a data store.
  - [scrollable_positioned_list](https://github.com/google/flutter.widgets/blob/master/packages/scrollable_positioned_list/README.md) - A flutter list that allows scrolling to a specific item in the list. Also allows determining what items are currently visible.
  - [linked_scroll_controller](https://github.com/google/flutter.widgets/blob/master/packages/linked_scroll_controller/README.md) - This package provides a way to set up a set of scrollable widgets whose scrolling is synchronized. The set can be stable across the lifetime of the containing screen, or can change dynamically (for example, a vertically scrolling ListView.builder() whose items are Scrollables that scroll horizontally in unison).
  - [flutter_simple_treeview](https://github.com/google/flutter.widgets/blob/master/packages/flutter_simple_treeview/README.md) - This widget visualises a tree structure, where a node can be any widget.

- ![](https://img.shields.io/github/stars/aagarwal1012/IntroViews-Flutter?style=social) [IntroViews-Flutter](https://github.com/aagarwal1012/IntroViews-Flutter) - IntroViews is inspired by [Paper Onboarding](https://github.com/Ramotion/paper-onboarding-android) and developed with love from scratch. Checkout our fully responsive [live example app](https://introviews-flutter.web.app/).

## Add Flutter to existing app

- 💗💗👍👍![](https://img.shields.io/github/stars/alibaba/flutter_boost?style=social) [flutter_boost@alibabba](https://github.com/alibaba/flutter_boost) -  A next-generation Flutter-Native hybrid solution. FlutterBoost is a Flutter plugin which enables hybrid integration of Flutter for your existing native apps with minimum efforts.The philosophy of FlutterBoost is to use Flutter as easy as using a WebView. Managing Native pages and Flutter pages at the same time is non-trivial in an existing App. FlutterBoost takes care of page resolution for you. The only thing you need to care about is the name of the page(usually could be an URL).
- ![](https://img.shields.io/github/stars/hellobike/flutter_thrio?style=social) [flutter_thrio @hellobike](https://github.com/hellobike/flutter_thrio)

## Navigation & Routing

- 💗🤔👀 ![](https://img.shields.io/github/stars/theyakka/fluro?style=social) [fluro](https://github.com/theyakka/fluro) -  The brightest, hippest, coolest router for Flutter.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png">  ![](https://img.shields.io/github/stars/lejard-h/chopper?style=social)  [chopper](https://github.com/lejard-h/chopper) -  Chopper is an http client generator for Dart and Flutter using source_gen and inspired by Retrofit.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png">![](https://img.shields.io/github/stars/slovnicki/beamer?style=social) [](https://github.com/slovnicki/beamer) - A Flutter package to help you handle your application routing and synchronize it with browser URL. Beamer uses the power of Router and implements all the underlying logic for you.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png">![](https://img.shields.io/github/stars/csells/go_router?style=social) [go_router](https://github.com/csells/go_router) - The purpose of the go_router package is to use declarative routes to reduce complexity, regardless of the platform you're targeting (mobile, web, desktop), handle deep and dynamic linking from Android, iOS and the web, along with a number of other navigation-related scenarios, while still (hopefully) providing an easy-to-use developer experience.
- ![](https://img.shields.io/github/stars/felangel/flow_builder?style=social) [flow_builder](https://github.com/felangel/flow_builder) - Flutter Flows made easy!

## Data & Backend

- ![](https://img.shields.io/github/stars/ReactiveX/rxdart?style=social) [RxDart](https://github.com/ReactiveX/rxdart) - RxDart extends the capabilities of Dart Streams and StreamControllers.

  Dart comes with a very decent Streams API out-of-the-box; rather than attempting to provide an alternative to this API, RxDart adds functionality from the reactive extensions specification on top of it.

  RxDart does not provide its Observable class as a replacement for Dart Streams. Instead, it offers several additional Stream classes, operators (extension methods on the Stream class), and Subjects.

  If you are familiar with Observables from other languages, please see the [Rx Observables vs. Dart Streams comparison chart](https://github.com/ReactiveX/rxdart#rx-observables-vs-dart-streams) for notable distinctions between the two.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> Google! [json_serializable](https://github.com/google/json_serializable.dart/tree/master/json_serializable) - Provides Dart Build System builders for handling JSON.
  The builders generate code when they find members annotated with classes defined in package:json_annotation.

  To generate to/from JSON code for a class, annotate it with JsonSerializable. You can provide arguments to JsonSerializable to configure the generated code. You can also customize individual fields by annotating them with JsonKey and providing custom arguments. See the table below for details on the annotation values.

  To generate a Dart field with the contents of a file containing JSON, use the JsonLiteral annotation.

- ![](https://img.shields.io/github/stars/k-paxian/dart-json-mapper?style=social) [dart_json_mapper](https://github.com/k-paxian/dart-json-mapper) - This package allows programmers to annotate Dart objects in order to Serialize / Deserialize them to / from JSON.

### Storage

- ![](https://img.shields.io/github/stars/hivedb/hive?style=social) [hive](https://github.com/hivedb/hive) - Hive is a lightweight and blazing fast key-value database written in pure Dart. Inspired by Bitcask.

  If you need queries, multi-isolate support or links between objects check out Isar Database.
  Features
  - 🚀 Cross platform: mobile, desktop, browser
  - ⚡ Great performance (see benchmark)
  - ❤️ Simple, powerful, & intuitive API
  - 🔒 Strong encryption built in
  - 🎈 NO native dependencies
  - 🔋 Batteries included
- ![](https://img.shields.io/github/stars/isar/isar?style=social) [Isar Database](https://github.com/isar/isar)
  - 💙 Made for Flutter. Easy to use, no config, no boilerplate
  - 🚀 Highly scalable from hundreds to hundreds of thousands of records
  - 🍭 Feature rich. Composite & multi indexes, query modifiers, JSON support and more
  - 🔎 Full-text search. Make searching fast and fun
  - 📱 Multiplatform. iOS, Android, Desktop and the web (soon™)
  - 🧪 ACID semantics. Rely on consistency
  - ⏱ Asynchronous. Parallel query operations & multi-isolate support
  - 💃 Static typing. Compile-time checked and autocompleted queries

- ![](https://img.shields.io/github/stars/vitusortner/floor?style=social) [floor](https://github.com/vitusortner/floor) - Floor provides a neat SQLite abstraction for your Flutter applications inspired by the Room persistence library. It comes with automatic mapping between in-memory objects and database rows while still offering full control of the database with the use of SQL. As a consequence, it's necessary to have an understanding of SQL and SQLite in order to harvest Floor's full potential.

- ![](https://img.shields.io/github/stars/realm/realm-dart?style=social) [Realm](https://github.com/realm/realm-dart) -  a mobile database that runs directly inside phones, tablets or wearables. This repository holds the source code for the Realm SDK for Flutter™ and Dart™.
- ![](https://img.shields.io/github/stars/lesnitsky/flutter_localstorage?style=social) [flutter_localstorage](https://github.com/lesnitsky/flutter_localstorage) - Simple json file-based storage for flutter

- ![](https://img.shields.io/github/stars/flutterdata/flutter_data?style=social) [flutter_data](https://github.com/flutterdata/flutter_data/) - Persistent reactive models in Flutter with zero boilerplate. Flutter Data is an offline-first persistence framework that gives you a configurable REST client and powerful model relationships. Heavily inspired by [Ember Data](https://github.com/emberjs/data) and [ActiveRecord](https://guides.rubyonrails.org/active_record_basics.html)

### State management

- ![](https://img.shields.io/github/stars/felangel/bloc?style=social) [felangel/bloc](https://github.com/felangel/bloc) - A predictable state management library that helps implement the [BLoC design pattern](https://www.didierboelens.com/2018/08/reactive-programming-streams-bloc/).
- ![](https://img.shields.io/github/stars/alibaba/fish-redux?style=social) [alibaba/fish-redux](https://github.com/alibaba/fish-redux) - is an assembled flutter application framework based on Redux state management. It is suitable for building medium and large applications.

  It has four characteristics:

  - Functional Programming
  - Predictable state container
  - Pluggable componentization
  - Non-destructive performance
- ![](https://img.shields.io/github/stars/jonataslaw/getx?style=social) [getx](https://github.com/jonataslaw/getx) - GetX is an extra-light and powerful solution for Flutter. It combines high-performance state management, intelligent dependency injection, and route management quickly and practically. GetX has 3 basic principles. This means that these are the priority for all resources in the library: PRODUCTIVITY, PERFORMANCE AND ORGANIZATION.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/rrousselGit/provider?style=social) [provider](https://github.com/rrousselGit/provider) - A wrapper around InheritedWidget to make them easier to use and more reusable.

  By using provider instead of manually writing InheritedWidget, you get:
  - simplified allocation/disposal of resources
  - lazy-loading
  - a vastly reduced boilerplate over making a new class every time
  - devtool friendly – using Provider, the state of your application will be visible in the Flutter devtool
  - a common way to consume these InheritedWidgets (See Provider.of/Consumer/Selector)
  - increased scalability for classes with a listening mechanism that grows exponentially in complexity (such as ChangeNotifier, which is O(N) for dispatching notifications).
- ![](https://img.shields.io/github/stars/rrousselGit/river_pod?style=social) [river_pod](https://github.com/rrousselGit/river_pod) - A state-management library that:
  - catches programming errors at compile time rather than at runtime
  - removes nesting for listening/combining objects
  - ensures that the code is testable
  
  This project can be considered as a rewrite of provider to make improvements that would be otherwise impossible.

  For learning how to use Riverpod, see its documentation: <https://riverpod.dev>

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/mobxjs/mobx.dart?style=social)  [mobx](https://github.com/mobxjs/mobx.dart) - MobX is a state-management library that makes it simple to connect the reactive data of your application with the UI. This wiring is completely automatic and feels very natural. As the application-developer, you focus purely on what reactive-data needs to be consumed in the UI (and elsewhere) without worrying about keeping the two in sync.

  It's not really magic but it does have some smarts around what is being consumed (observables) and where (reactions), and automatically tracks it for you. When the observables change, all reactions are re-run. What's interesting is that these reactions can be anything from a simple console log, a network call to re-rendering the UI.

  > MobX has been a very effective library for the JavaScript apps and this port to the Dart language aims to bring the same levels of productivity.

- ![](https://img.shields.io/github/stars/brianegan/scoped_model?style=social) [scoped_model](https://github.com/brianegan/scoped_model) - A set of utilities that allow you to easily pass a data Model from a parent Widget down to its descendants. In addition, it also rebuilds all of the children that use the model when the model is updated. This library was originally extracted from the Fuchsia codebase.

### Network

- ![](https://img.shields.io/github/stars/flutterchina/dio?style=social) [dio](https://github.com/flutterchina/dio) - A powerful Http client for Dart, which supports Interceptors, Global configuration, FormData, Request Cancellation, File downloading, Timeout etc.
- **DART OFFICIAL** ![](https://img.shields.io/github/stars/dart-lang/http?style=social)  [dart-lang/http](https://github.com/dart-lang/http) - A composable, Future-based library for making HTTP requests. This package contains a set of high-level functions and classes that make it easy to consume HTTP resources. It's multi-platform, and supports mobile, desktop, and the browser.

## Components

### UI Kits

- ![](https://img.shields.io/github/stars/mitesh77/Best-Flutter-UI-Templates?style=social) [💗Best-Flutter-UI-Templates](https://github.com/mitesh77/Best-Flutter-UI-Templates)
- ![](https://img.shields.io/github/stars/iampawan/Flutter-UI-Kit?style=social) [Flutter-UI-Kit: Flutter app for collection of UI in a UIKit](https://github.com/iampawan/Flutter-UI-Kit)
- ![](https://img.shields.io/github/stars/nb312/flutter-ui-nice?style=social) [flutter-ui-nice](https://github.com/nb312/flutter-ui-nice)
- ![](https://img.shields.io/github/stars/ionicfirebaseapp/getwidget?style=social) [getwidget](https://github.com/ionicfirebaseapp/getwidget) - Most popular and easy to use open source UI library with 1000+ Widgets to build flutter app.
- ![](https://img.shields.io/github/stars/Rannie/flui?style=social) [flui](https://github.com/Rannie/flui) -  A powerful UI framework for Google Flutter. <https://www.flui.xin/en/>
- ![](https://img.shields.io/github/stars/olayemii/flutter-ui-kits?style=social) [flutter-ui-kits](https://github.com/olayemii/flutter-ui-kits) - Free Flutter UI Kits based on designs on UpLabs 💓. Includes Wrist Watch Store UI Kit, Language Learning FLutter UI Kit, News UI Flutter UI Kit, Real Estate Flutter UI Kit, Repair Service Flutter UI Kit, AirBnB Redesign Flutter UI Kit, Laundry App Flutter UI Kit.

### Color

- ![](https://img.shields.io/github/stars/bregydoc/pigment?style=social) [pigment](https://github.com/bregydoc/pigment) - A simple but useful plugin for use colors with Flutter.
  - You can use string colors (like #01E19F) direct in flutter
  - Pigment extends to Color dar:ui class, then you can use all methods of Color class
  - Pigment 1.0.1 can parse 'rgb()' (e.g. 'rgb(29, 123, 10)').
  - Added CSS colors with default name, you can access from this with CSSColor.* (e.g. Pigment.fromCSSColor(CSSColor.lightsalmon)) or directly with Pigment.fromString('lightsalmon').

### Text

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/leisim/auto_size_text?style=social)[AutoSizeText](https://github.com/leisim/auto_size_text) - Flutter widget that automatically resizes text to fit perfectly within its bounds.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/aagarwal1012/Animated-Text-Kit?style=social) [Animated-Text-Kit](https://github.com/aagarwal1012/Animated-Text-Kit) - A flutter package which contains a collection of some cool and awesome text animations. Recommended package for text animations in Codemagic's Ebook, "Flutter libraries we love". Try out our live [example app](https://animated-text-kit.web.app/#/).
    ![](https://github.com/aagarwal1012/Animated-Text-Kit/raw/master/display/cover.gif?raw=true)
- ![](https://img.shields.io/github/stars/bytedance/RealRichText?style=social) [RealRichText](https://github.com/bytedance/RealRichText) - A Tricky Solution for Implementing Inline-Image-In-Text Feature in Flutter.

- ![](https://img.shields.io/github/stars/marcelgarus/marquee?style=social) [marquee](https://github.com/marcelgarus/marquee) - A Flutter widget that scrolls text infinitely. Provides many customizations including custom scroll directions, durations, curves as well as pauses after every round.

### Icon

- ![](https://img.shields.io/github/stars/fluttercommunity/font_awesome_flutter?style=social) [font_awesome_flutter](https://github.com/fluttercommunity/font_awesome_flutter) - The [Font Awesome](https://fontawesome.com/icons) Icon pack available as set of Flutter Icons.
- ![](https://img.shields.io/github/stars/flutter-studio/flutter-icons?style=social) [flutter_icons](https://github.com/flutter-studio/flutter-icons) -  Customizable Icons for Flutter,Inspired by react-native-vector-icons.  
  Bundled Icon Sets:
  - AntDesign by AntFinance (297 icons)
  - Entypo by Daniel Bruce (411 icons)
  - EvilIcons by Alexander Madyankin & Roman Shamin (v1.10.1, 70 icons)
  - Feather by Cole Bemis & Contributors (v4.7.0, 266 icons)
  - FontAwesome by Dave Gandy (v4.7.0, 675 icons)
  - FontAwesome 5 by Fonticons, Inc. (v5.7.0, 1500 (free))
  - Foundation by ZURB, Inc. (v3.0, 283 icons)
  - Ionicons by Ben Sperry (v4.2.4, 696 icons)
  - MaterialIcons by Google, Inc. (v3.0.1, 932 icons)
  - MaterialCommunityIcons by MaterialDesignIcons.com (v4.0.96, 4416 icons)
  - Octicons by Github, Inc. (v8.0.0, 177 icons)
  - Zocial by Sam Collins (v1.0, 100 icons)
  - SimpleLineIcons by Sabbir & Contributors (v2.4.1, 189 icons)
  - Weather Icons by erikflowers (v2.0.10, 596 icons)
- ![](https://img.shields.io/github/stars/iconfont-cli/flutter-iconfont-cli?style=social) [flutter-iconfont-cli](https://github.com/iconfont-cli/flutter-iconfont-cli) - 用纯 JS 把 [iconfont](https://www.iconfont.cn/) 的图标转换成Flutter Widget，不依赖字体，支持多色彩

### Toast & Loading & Refresh

- ![](https://img.shields.io/github/stars/CoderMJLee/MJRefresh?style=social) [MJRefresh](https://github.com/CoderMJLee/MJRefresh) - An easy way to use pull-to-refresh
- ![](https://img.shields.io/github/stars/xuelongqy/flutter_easyrefresh?style=social) [flutter_easyrefresh](https://github.com/xuelongqy/flutter_easyrefresh)
- ![](https://img.shields.io/github/stars/jogboms/flutter_spinkit?style=social) [Flutter Spinkit](https://github.com/jogboms/flutter_spinkit) - A collection of loading indicators animated with flutter. Heavily inspired by @tobiasahlin's SpinKit.
- ![](https://img.shields.io/github/stars/peng8350/flutter_pulltorefresh?style=social) [flutter_pulltorefresh](https://github.com/peng8350/flutter_pulltorefresh) - a widget provided to the flutter scroll component drop-down refresh and pull up load.support android and ios.

- ![](https://img.shields.io/github/stars/ponnamkarthik/FlutterToast?style=social) [FlutterToast](https://github.com/ponnamkarthik/FlutterToast) - this toast library supports two kinds of toast messages one which requires BuildContext other with No BuildContext(Powered by platform channel!). Supported Platforms: Android, iOS, Web (Uses Toastify-JS)

- ![](https://img.shields.io/github/stars/aagarwal1012/Liquid-Pull-To-Refresh?style=social) [Liquid-Pull-To-Refresh](https://github.com/aagarwal1012/Liquid-Pull-To-Refresh) - A beautiful and custom refresh indicator for flutter highly inspired from [Ramotion Pull Down](https://dribbble.com/shots/1797373-Pull-Down-To-Refresh) to Refresh. Try out our live [example app](https://liquid-pull-to-refresh.web.app/#/).

- ![](https://img.shields.io/github/stars/MMMzq/bot_toast?style=social) [💗 bot_toast](<https://github.com/MMMzq/bot_toast> -: A really easy to use flutter toast library!
  - In the true sense of Toast, you can call it whenever you need it, without any restrictions!
  - Feature-rich, support for displaying notifications, text, loading, attachments, etc. Toast
  - Support for popping up various custom Toasts, or you can pop up any Widget as long as it meets the requirements of the flutter code.
  - API is simple and easy to use
  - Pure flutter implementation
- ![](https://img.shields.io/github/stars/OpenFlutter/flutter_oktoast?style=social) [flutter_oktoast](https://github.com/OpenFlutter/flutter_oktoast) - A pure dart toast Library. You can completely customize the style of toast.
- ![](https://img.shields.io/github/stars/appdev/FlutterToast?style=social) [FlutterToast](https://github.com/appdev/FlutterToast)
- ![](https://img.shields.io/github/stars/bytedance/pull_to_refresh?style=social) [bytedance pull_to_refresh](https://github.com/bytedance/pull_to_refresh) - A widget that provided to pull-up load and pull-down refresh with Flutter.

### Dialog & Alert

- ![](https://img.shields.io/github/stars/YYFlutter/flutter-custom-dialog?style=social)  [flutter-custom-dialog](https://github.com/YYFlutter/flutter-custom-dialog) - Global dialog function encapsulation, with a semantic way to fill the content inside the dialog, the current function provided
  1. Support for a few semantic component methods to populate the component content inside dialog
  1. Support for customizing semantic components for developers to freely populate component content inside dialog
  1. Support setting dialog background color, foreground color, position, animation, click the external disappear and other functions, see the details below
  1. Support no Context call dialog, see below

- ![](https://img.shields.io/github/stars/RatelHub/rflutter_alert?style=social) [rflutter_alert](https://github.com/RatelHub/rflutter_alert) - RFlutter Alert is super customizable and easy-to-use alert/popup dialogs for Flutter. You may create reusable alert styles or add buttons as much as you want with ease.

### Popup

### Picker

- ![](https://img.shields.io/github/stars/fluttercandies/flutter_wechat_assets_picker?style=social) [wechat_assets_picker](https://github.com/fluttercandies/flutter_wechat_assets_picker) - An assets picker which based on the WeChat's UI, using photo_manager for asset implementation, extended_image for image preview, and provider to help control the state of the picker.

  To take a photo or a video for assets, please check the detailed usage in the example, and head over to [wechat_camera_picker](https://pub.dev/packages/wechat_camera_picker).

  All UI designs are based on WeChat 8.x, and it will be updated following the WeChat update in anytime.
- ![](https://img.shields.io/github/stars/yangyxd/flutter_picker?style=social) [flutter_picker](https://github.com/yangyxd/flutter_picker) - Flutter plugin picker. Include NumberPicker, DateTimePicker, ArrayPicker, and default linkage Picker. Provide flexible parameters to meet various needs. At the same time, you can extend more functions through custom adapters.

- ![](https://img.shields.io/github/stars/mchome/flutter_colorpicker?style=social) [flutter_colorpicker](https://github.com/mchome/flutter_colorpicker) - HSV(HSB)/HSL/RGB/Material color picker inspired by all the good design for your amazing flutter apps.
Adorable color pickers out of the box with highly customized widgets to all developers' needs. [Web Example](https://mchome.github.io/flutter_colorpicker)

### Bar

- ![](https://img.shields.io/github/stars/hacktons/convex_bottom_bar?style=social) [convex_bottom_bar](https://github.com/hacktons/convex_bottom_bar) - The official BottomAppBar can only display a notch FAB with app bar, sometimes we need a convex FAB. This ConvexAppBar is inspired by BottomAppBar and NotchShape's implementation. Online example can be found at <https://appbar.codemagic.app>. convex_bottom_bar is now a **Flutter Favorite package**!

### Chart

- ![](https://img.shields.io/github/stars/imaNNeoFighT/fl_chart?style=social) [fl_chart](https://github.com/imaNNeoFighT/fl_chart) - A powerful Flutter chart library, currently supporting Line Chart, Bar Chart, Pie Chart and Scatter Chart.

- ![](https://img.shields.io/github/stars/google/charts?style=social) [](https://github.com/google/charts) - Charts is a general charting library, currently enabled for the Flutter mobile UI framework.

  See [the online gallery](https://google.github.io/charts/flutter/gallery.html) for supported chart types and examples of how to custom components of the chart.

  Note: This is not an official Google product.

### Switch

- ![](https://img.shields.io/github/stars/boringdeveloper/FlutterSwitch?style=social) [FlutterSwitch](https://github.com/boringdeveloper/FlutterSwitch) - An easy to implement custom switch created for Flutter. Give it a custom height and width, border for the switch and toggle, border radius, colors, toggle size, a choice to display an 'On' and 'Off' text and able to add an icon inside the toggle.

### Swipe & Slide & Indicator

- ![](https://img.shields.io/github/stars/best-flutter/flutter_swiper?style=social) [flutter_swiper](https://github.com/best-flutter/flutter_swiper) - The best swiper for flutter , with multiple layouts, infinite loop. Compatible with Android & iOS.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/letsar/flutter_slidable?style=social)  [flutter_slidable](https://github.com/letsar/flutter_slidable) - A Flutter implementation of slidable list item with directional slide actions that can be dismissed.
- ![](https://img.shields.io/github/stars/akshathjain/sliding_up_panel?style=social) [sliding_up_panel](https://github.com/akshathjain/sliding_up_panel) - A draggable Flutter widget that makes implementing a SlidingUpPanel much easier! Based on the Material Design bottom sheet component, this widget works on both Android & iOS. (like DouBan)
- ![](https://img.shields.io/github/stars/Milad-Akarie/smooth_page_indicator?style=social) [smooth_page_indicator](https://github.com/Milad-Akarie/smooth_page_indicator) - Customizable animated page indicator with a set of built-in effects.

### Badges & Labels

- ![](https://img.shields.io/github/stars/yako-dev/flutter_badges?style=social) [flutter_badges](https://github.com/yako-dev/flutter_badges)

### Datetime

- ![](https://img.shields.io/github/stars/Realank/flutter_datetime_picker?style=social) [Flutter Datetime Picker](https://github.com/Realank/flutter_datetime_picker) - A flutter date time picker inspired by flutter-cupertino-date-picker

### Calendars

- ![](https://img.shields.io/github/stars/aleksanderwozniak/table_calendar?style=social) [table_calendar](https://github.com/aleksanderwozniak/table_calendar) - Highly customizable, feature-packed Flutter Calendar with gestures, animations and multiple formats

### Clippers

- ![](https://img.shields.io/github/stars/lohanidamodar/flutter_custom_clippers?style=social) [flutter_custom_clippers](https://github.com/lohanidamodar/flutter_custom_clippers) - Flutter package that provides you custom clippers to help you achieve various custom shapes.

### Images

- ![](https://img.shields.io/github/stars/fluttercandies/extended_image?style=social) [extended_image](https://github.com/fluttercandies/extended_image) - A powerful official extension library of image, which support placeholder(loading)/ failed state, cache network, zoom pan image, photo view, slide out page, editor(crop,rotate,flip), paint custom etc.
- ![](https://img.shields.io/github/stars/dnfield/flutter_svg?style=social) [flutter_svg](https://github.com/dnfield/flutter_svg) - Draw SVG (and some Android VectorDrawable (XML)) files on a Flutter Widget.

### List & Grid

- ![](https://img.shields.io/github/stars/letsar/flutter_staggered_grid_view?style=social) [flutter_staggered_grid_view](https://github.com/letsar/flutter_staggered_grid_view) - Provides a collection of Flutter grids layouts. This package contains various grid layouts. In the following section, you'll discover each one of them. The explanation of the layout will always considered a top-to-bottom and left-to-right directions to simplify the description. However it is possible to change these directions in the code.
- [flutterchina/azlistview](https://github.com/flutterchina/azlistview) - A Flutter sticky headers & index ListView. Based on scrollable_positioned_list.
AzListView, SuspensionView, IndexBar.
Easy creation of city list or contact list interfaces.
  - List items can be grouped A-Z.
  - Sticky headers with floating option.
  - Support custom header.
  - Support index linkage.
  - IndexBar supports custom styles.
  - IndexBar supports local images.
  - Allows scrolling to a specific item in the list.

- ![](https://img.shields.io/github/stars/fluttercommunity/flutter_sticky_headers?style=social) [flutter_sticky_headers](https://github.com/fluttercommunity/flutter_sticky_headers) - Lets you place headers on scrollable content that will stick to the top of the container whilst the content is scrolled.

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/EdsonBueno/infinite_scroll_pagination?style=social) [infinite_scroll_pagination](https://github.com/EdsonBueno/infinite_scroll_pagination) - Unopinionated, extensible and highly customizable package to help you lazily load and display small chunks of items as the user scrolls down the screen – known as infinite scrolling pagination, endless scrolling pagination, auto-pagination, lazy loading pagination, progressive loading pagination, etc.

  Designed to feel like part of the Flutter framework.
- ![](https://img.shields.io/github/stars/fluttercommunity/flutter_infinite_listview?style=social) [flutter_infinite_listview](https://github.com/fluttercommunity/flutter_infinite_listview) - ListView with items that can be scrolled infinitely in both directions.
- ![](https://img.shields.io/github/stars/marcglasberg/indexed_list_view?style=social) [indexed_list_view](https://github.com/marcglasberg/indexed_list_view) - Similar to a ListView, but lets you programmatically jump to any item, by index. The index jump happens instantly, no matter if you have millions of items.

  Limitation: The list is always infinite both to positive and negative indexes. In other words, it can be scrolled indefinitely both to the top and to the bottom.

### Form

- ![](https://img.shields.io/github/stars/danvick/flutter_form_builder?style=social) [Flutter Form Builder](https://github.com/danvick/flutter_form_builder) - Flutter Form Builder provides an easy way of working with forms in Flutter by removing the boilerplate needed to build a form, validate fields, react to changes, and collect final user input.

### Steps & Timelines

- ![](https://img.shields.io/github/stars/chulwoo-park/timelines?style=social) [timelines](https://github.com/chulwoo-park/timelines/) - A powerful & easy to use timeline package for Flutter! (This package is an early stage. Not enough testing has been done to guarantee stability. Some APIs may change. 2021-12-29)

### Progress

- ![](https://img.shields.io/github/stars/diegoveloper/flutter_percent_indicator?style=social) [flutter_percent_indicator](https://github.com/diegoveloper/flutter_percent_indicator) - Circular and Linear percent indicators:
  - Circle percent indicator
  - Linear percent indicator
  - Toggle animation
  - Custom duration of the animation
  - Progress based on a percentage value
  - Progress and background color
  - Custom size
  - Left , right or center child for Linear percent indicator
  - Top, bottom or center child for Circular percent indicator
  - Progress Color using gradients

### Editor

- ![](https://img.shields.io/github/stars/singerdmx/flutter-quill?style=social) [flutter-quill](https://github.com/singerdmx/flutter-quill) - FlutterQuill is a rich text editor and a Quill component for Flutter.

  This library is a WYSIWYG editor built for the modern mobile platform, with web compatibility under development. Check out our Youtube Playlist to take a detailed walkthrough of the code base. You can join our Slack Group for discussion.

  Demo App: <https://bulletjournal.us/home/index.html>

### Effect

- ![](https://img.shields.io/github/stars/2d-inc/Flare-Flutter?style=social) [Flare-Flutter](https://github.com/2d-inc/Flare-Flutter) - Rive 1 (previously Flare) offers powerful realtime vector design and animation for app and game designers alike. The primary goal of Flare is to allow designers to work directly with assets that run in their final product, eliminating the need to redo that work in code.
- ![](https://img.shields.io/github/stars/xvrh/lottie-flutter?style=social)  [Lottie for Flutter](https://github.com/xvrh/lottie-flutter) - Lottie is a mobile library for Android and iOS that parses Adobe After Effects animations exported as json with Bodymovin and renders them natively on mobile!

  This repository is an unofficial conversion of the Lottie-android library in pure Dart.

  It works on Android, iOS, macOS, linux, windows and web.
- ![](https://img.shields.io/github/stars/YYFlutter/flutter-animation-set?style=social)   [flutter-animation-set](https://github.com/YYFlutter/flutter-animation-set) - Simplified Flutter stagger animation.To drive the Flutter stagger animation through a timeline in the form of an animation configuration.You can

  1. Uses the existing Animation Widget of Flutter Animation Set
  2. Use Flutter Animation Set to create a new Animation Widget
  3. Contribute your Flutter Animation Set Widget
  4. Watch All of the Curves of Flutter in example

## Plugins

- ![](https://img.shields.io/github/stars/FirebaseExtended/flutterfire?style=social) [FlutterFire](https://github.com/FirebaseExtended/flutterfire) - FlutterFire is a set of Flutter plugins that enable Flutter apps to use Firebase services. You can follow an example that shows how to use these plugins in the Firebase for Flutter codelab.

  Flutter is Google’s UI toolkit for building beautiful, natively compiled applications for mobile, web, and desktop from a single codebase. Flutter is used by developers and organizations around the world, and is free and open source.
- ![](https://img.shields.io/github/stars/OpenFlutter/flutter_screenutil?style=social) [flutter_screenutil](https://github.com/OpenFlutter/flutter_screenutil) - A flutter plugin for adapting screen and font size.Let your UI display a reasonable layout on different screen sizes!

- ![](https://img.shields.io/github/stars/fluttercommunity/flutter_downloader?style=social) [flutter_downloader](https://github.com/fluttercommunity/flutter_downloader) - A plugin for creating and managing download tasks. Supports iOS and Android.

  This plugin is based on WorkManager in Android and NSURLSessionDownloadTask in iOS to run download task in background mode.

- ![](https://img.shields.io/github/stars/diegoveloper/flutter_keyboard_actions?style=social) [flutter_keyboard_actions](https://github.com/diegoveloper/flutter_keyboard_actions/) - Add features to the Android / iOS keyboard in a simple way.

Because the keyboard that Android / iOS offers us specifically when we are in numeric mode, does not bring the button to hide the keyboard. This causes a lot of inconvenience for users, so this package allows adding functionality to the existing keyboard.

- ![](https://img.shields.io/github/stars/creativecreatorormaybenot/wakelock?style=social) [Wakelock](https://github.com/creativecreatorormaybenot/wakelock) - Wakelock is Flutter plugin that allows you to keep the device screen awake, i.e. prevent the screen from sleeping.
- ![](https://img.shields.io/github/stars/fluttercommunity/flutter_uploader?style=social) [flutter_uploader](https://github.com/fluttercommunity/flutter_uploader) - A plugin for creating and managing upload tasks. Supports iOS and Android.

  This plugin is based on WorkManager in Android and NSURLSessionUploadTask in iOS to run upload task in background mode.

  This plugin is inspired by flutter_downloader. Thanks to Hung Duy Ha & Flutter Community for great plugins and inspiration.

**Plugins productivity**:

- ![](https://img.shields.io/github/stars/dart-native/dart_native?style=social)  [Dart_Native](https://github.com/dart-native/dart_native) - Dart_Native operates as both a code generator tool and a bridge to communicate between Dart and native APIs.

  Replaces the low-performing Flutter channel with faster and more concise code

## Utils

- ![](https://img.shields.io/github/stars/Sub6Resources/flutter_html?style=social) [flutter_html](https://github.com/Sub6Resources/flutter_html) - A Flutter widget for rendering HTML and CSS as Flutter widgets.

- ![](https://img.shields.io/github/stars/google/quiver-dart?style=social) [google/quiver-dart](https://github.com/google/quiver-dart) - Quiver is a set of utility libraries for Dart that makes using many Dart libraries easier and more convenient, or adds additional functionality. [👉 API Doc](https://pub.dev/documentation/quiver/latest/)

- ![](https://img.shields.io/github/stars/flutterchina/lpinyin?style=social) [lpinyin](https://github.com/flutterchina/lpinyin) - 汉字转拼音
- ❗️GOOGLE❗️ ![](https://img.shields.io/github/stars/google/reflectable.dart?style=social) [reflectable.dart](https://github.com/google/reflectable.dart) - This repository provides the Dart package reflectable along with a set of test cases, test_reflectable.

- ![](https://img.shields.io/github/stars/mmcc007/screenshots?style=social) [Screenshots](https://github.com/mmcc007/screenshots) - A screenshot image with overlaid status bar placed in a device frame. Screenshots is a standalone command line utility and package for capturing screenshot images for Flutter.

  Screenshots will start the required android emulators and iOS simulators (or find attached devices), run tests, process the captured screenshots, and drop them off to Fastlane for delivery to both stores.

  Screenshots is inspired by three tools from Fastlane:

  1. [Snapshots](https://docs.fastlane.tools/getting-started/ios/screenshots/)
  This is used to capture screenshots on iOS using iOS UI Tests.
  2. [Screengrab](https://docs.fastlane.tools/actions/screengrab/)
  This captures screenshots on android using Android Espresso tests.
  3. [FrameIt](https://docs.fastlane.tools/actions/frameit/)
  This is used to place captured iOS screenshots in a device frame.

  Since all three of these Fastlane tools do not work with Flutter, Screenshots combines key features of these Fastlane tools into one tool.
- ![](https://img.shields.io/github/stars/ganeshrvel/pub-rules?style=social)[Rules](https://github.com/ganeshrvel/pub-rules) - Powerful and feature-rich validation library for both Dart and Flutter.
  - Highly flexible
  - Easy to understand
  - Less boilerplate code
  - Custom error handling
  - Override individual errors
  - Flutter friendly
  - State management libraries friendly (Mobx example included)

**Dart Extend**:

- ![](https://img.shields.io/github/stars/Ephenodrom/Dart-Basic-Utils?style=social) [Dart-Basic-Utils](https://github.com/Ephenodrom/Dart-Basic-Utils) - A dart package for many helper methods fitting different situations. String, Domain, Email, Math, HTTP, DNS, Sort, Color, Date, Iterable, Crypto, ASN1, FunctionDefs, X509....
- ![](https://img.shields.io/github/stars/dart-lang/collection?style=social) [dart-lang/collection](https://github.com/dart-lang/collection)(**Dart Official**) - Contains utility functions and classes in the style of dart:collection to make working with collections easier. Includes Algorithms, Equality, Iterable Zip, Priority Queue, Wrappers...

**Lifecycle**

- ![](https://img.shields.io/github/stars/rrousselGit/flutter_hooks?style=social) [flutter_hooks](https://github.com/rrousselGit/flutter_hooks) - A Flutter implementation of React hooks: <https://medium.com/@dan_abramov/making-sense-of-react-hooks-fdbde8803889>.
Hooks are a new kind of object that manage the life-cycle of a Widget. They exist for one reason: increase the code-sharing between widgets by removing duplicates.

- ![](https://img.shields.io/github/stars/fluttercommunity/flutter_after_layout?style=social) [flutter_after_layout](https://github.com/fluttercommunity/flutter_after_layout) - Brings functionality to execute code after the first layout of a widget has been performed, i.e. after the first frame has been displayed.

**Screen**

- ![](https://img.shields.io/github/stars/xamantra/relative_scale?style=social)[relative_scale](https://github.com/xamantra/relative_scale) - RelativeScale is a simple custom sizing system for flutter widgets to achieve the same physical sizes across different devices.

**Code generator**

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> [pigeon](https://github.com/flutter/packages/tree/master/packages/pigeon) - Pigeon is a code generator tool to make communication between Flutter and the host platform type-safe, easier and faster.

- ![](https://img.shields.io/github/stars/flutter/packages?style=social) [Flutter Official packages pigeon](https://github.com/flutter/packages/tree/master/packages/pigeon) - Pigeon is a code generator tool to make communication between Flutter and the host platform type-safe, easier and faster.

- ![](https://img.shields.io/github/stars/FlutterGen/flutter_gen?style=social) [flutter_gen](https://github.com/FlutterGen/flutter_gen) - The Flutter code generator for your assets, fonts, colors, … — Get rid of all String-based APIs.

  Inspired by [SwiftGen](https://github.com/SwiftGen/SwiftGen).

- ![](https://img.shields.io/github/stars/dart-lang/build?style=social) [Dart Official Build](https://github.com/dart-lang/build) - These packages provide libraries for generating, compiling and serving Dart code.
  - build: Defines the interfaces for creating a Builder which is a way of doing codegen that is compatible across build systems (pub, bazel, standalone runner).

    For packages doing code generation this should generally be the only package against which there is a public dependency. Packages may have a dev_dependency on one or more of the other packages.

  - build_config: Support for parsing build.yaml files. Used by build_runner.
  - build_modules: Support for discovering the sub-modules within packages and creating summaries of those modules. Used by build_web_compilers but should not be used directly by most users.
  - build_resolvers: An implementation of the Resolver interface to use the analyzer during build steps.
  - build_runner: Provides utilities to enact builds and a way to automatically run builds based on configuration.

    This package should generally be a dev_dependency as it is used to run standalone builds. The only exception would be wrapping the build and watch methods with some other package.
  - build_test: Stub implementations for classes in Build and some utilities for running instances of builds and checking their outputs.

    This package generally only be a dev_dependency as it introduces a dependency on package:test. The exception to that would be if you were creating another testing-only package that wraps this one.
  - build_web_compilers: Provides the dart2js and dartdevc support for your package. To use this package you should add it as a dev_dependency.

    If you are using the automated build scripts, your project will automatically start being compiled with dartdevc, and you can start developing with chrome without any configuration.

- ![](https://img.shields.io/github/stars/dart-lang/source_gen?style=social) [dart-lang/source_gen](https://github.com/dart-lang/source_gen) - source_gen provides utilities for automated source code generation for Dart:
  - A framework for writing Builders that consume and produce Dart code.
  - A convention for human and tool generated Dart code to coexist with clean separation, and for multiple code generators to integrate in the same project.

  Its main purpose is to expose a developer-friendly API on top of lower-level packages like the analyzer or build. You don't have to use source_gen in order to generate source code; we also expose a set of library APIs that might be useful in your generators.

## Games

- ![](https://img.shields.io/github/stars/flame-engine/flame?style=social) [flame](https://github.com/flame-engine/flame) - A minimalist Flutter game engine

## CI/CD

- ![](https://img.shields.io/github/stars/f3ath/cider?style=social) [Cider(CI for Dart. Efficient Release)](https://github.com/f3ath/cider) - A command-line utility to automate package maintenance. Manipulates the changelog and pubspec.yaml.

  This tool assumes that the changelog:
  - is called CHANGELOG.md
  - is sitting in the project root folder
  - strictly follows the Keep a Changelog v1.0.0 format
  - uses basic markdown (no HTML and complex formatting supported)

**Lint & Format**

- ![](https://img.shields.io/github/stars/passsy/dart-lint?style=social)  [dart-lint](https://github.com/passsy/dart-lint) - lint is a hand-picked, open-source, community-driven collection of lint rules for Dart and Flutter projects. The set of rules follows the Effective Dart: Style Guide.

  This package can be used as a replacement for package:lints or the discontinued package:pedantic for those who prefer stricter rules.

  lint tries to be strict but not annoying.
- ![](https://img.shields.io/github/stars/fluttercommunity/import_sorter?style=social) [import_sorter](https://github.com/fluttercommunity/import_sorter) - 🎯 Dart package to automatically organize your dart imports. Any dart project supported! Will sorts imports alphabetically and then group them in the following order:
  1. Dart imports
  2. Flutter imports
  3. Package imports
  4. Project imports

## Monitor

- ![](https://img.shields.io/github/stars/dart-lang/stack_trace?style=social)  [dart-lang/stack_trace](https://github.com/dart-lang/stack_trace) - This library provides the ability to parse, inspect, and manipulate stack traces produced by the underlying Dart implementation. It also provides functions to produce string representations of stack traces in a more readable format than the native StackTrace implementation.

  Traces can be parsed from native StackTraces using Trace.from, or captured using Trace.current. Native StackTraces can also be directly converted to human-readable strings using Trace.format.

## Tools

- ![](https://img.shields.io/github/stars/aloisdeniel/flutter_device_preview?style=social) [Device Preview](https://github.com/aloisdeniel/flutter_device_preview) - Approximate how your app looks and performs on another device.
- ![](https://img.shields.io/github/stars/rxlabz/panache?style=social) [panache](https://github.com/rxlabz/panache) - A Flutter Material Theme editor. Panache helps you to create beautiful Material themes for your Flutter applications. Customize widgets colors and shapes, and download your theme.dart file.
- [fvm](https://github.com/befovy/fvm/) - Flutter Version Management: A simple cli to manage Flutter SDK versions.
  - Configure Flutter SDK version per project or globally
  - Ability to install and cache multiple Flutter SDK Versions
  - Easily switch between Flutter channels & versions

**Debug**:

- ![](https://img.shields.io/github/stars/bytedance/flutter_ume?style=social) [flutter_ume](https://github.com/bytedance/flutter_ume) - UME is an in-app debug kits platform for Flutter apps(Widget Info, Widget Detail, Align Ruler, Color Picker, Color Sucker, Touch Indicator, Memory Info, Perf Overlay, CPU Info, Device Info, Show Code, Console, Dio Inspector).
- ![](https://img.shields.io/github/stars/leoafarias/fvm?style=social)  [fvm](https://github.com/leoafarias/fvm) - Flutter Version Management: A simple cli to manage Flutter SDK versions.
- ![](https://img.shields.io/github/stars/nepaul/awesome-flutter?style=social)[logger](https://github.com/nepaul/awesome-flutter) - Small, easy to use and extensible logger which prints beautiful logs. Inspired by logger for Android.

**Docs**

- ![](https://img.shields.io/github/stars/glesica/dcdg.dart?style=social) [Dart Class Diagram Generator](https://github.com/glesica/dcdg.dart) - A small command line utility to generate a class (UML or similar) diagram from a Dart package.

## Apps

> Complete Projects(Open Source)

- ![](https://img.shields.io/github/stars/AppFlowy-IO/appflowy?style=social) [appflowy](https://github.com/AppFlowy-IO/appflowy) - Desktop App! The Open Source Notion Alternative(53+% Rust, 41+%Dart, C++...).
- ![](https://img.shields.io/github/stars/roughike/inKino?style=social) [inKino](https://github.com/roughike/inKino) - inKino is a multiplatform Dart app for browsing movies and showtimes for Finnkino cinemas.

  InKino showcases **Redux**, has an extensive set of automated tests and 40% code sharing between Flutter and web. The Android & iOS apps are made with a single Flutter codebase. The progressive web app is made with AngularDart. This project is generally something that I believe is a good example of a multiplatform Dart project.
- ![](https://img.shields.io/github/stars/TheAlphamerc/flutter_ecommerce_app?style=social) [flutter_ecommerce_app: E-Commerce App built in flutter](https://github.com/TheAlphamerc/flutter_ecommerce_app)
- ![](https://img.shields.io/github/stars/mdanics/fluttergram?style=social) [fluttergram](https://github.com/mdanics/fluttergram) - A working Instagram clone written in Flutter using Firebase / Firestore
- ![](https://img.shields.io/github/stars/aaronoe/FlutterCinematic?style=social) [❤️ FlutterCinematic](https://github.com/aaronoe/FlutterCinematic) - This app is a Flutter port of the native Android App [Cinematic](https://github.com/aaronoe/Cinematic). My intention in creating this app was understanding the intricacies of building apps in Flutter. Just like the native Android App this app does **not make any efforts in being a nicely architectured application**. That being said the whole point is to showcase Flutter's capabilities for building simple apps and to understand key difference and advantages to native development.
- ![](https://img.shields.io/github/stars/jesusrp98/spacex-go?style=social) [spacex-go](https://github.com/jesusrp98/spacex-go) - The purpose of this project is to develop the ultimate SpaceX experience in a variety of platforms. A single experience, from a single codebase.

  From the start, SpaceX GO! has been developed to be light-weight, fast and easy to use. It takes all the data from the open-source r/SpaceX REST API, which can be found [here](https://github.com/r-spacex/SpaceX-API).

- ![](https://img.shields.io/github/stars/matthewtory/trinity-orientation-2018?style=social) [Trinity Orientation 2018](https://github.com/matthewtory/trinity-orientation-2018) - An app created for Trinity College at University of Toronto. The app is acts as a companion for all first year students during orientation week. Available on [Google Play](https://play.google.com/store/apps/details?id=com.tory.trinityOrientation) and the [App Store](https://itunes.apple.com/us/app/trinity-orientation-2t2000s/id1431022073)

- ![](https://img.shields.io/github/stars/o1298098/Flutter-Movie?style=social) [Flutter-Movie](https://github.com/o1298098/Flutter-Movie) - 😎 🎬 A Flutter movie app build with **Fish-Redux** and The Movie DB api.

- ![](https://img.shields.io/github/stars/avirias/Grey?style=social) [Grey](https://github.com/avirias/Grey) -  A Material designed music player developed in Flutter

- ![](https://img.shields.io/github/stars/benoitletondor/Beer-Me-Up?style=social) [Beer-Me-Up](https://github.com/benoitletondor/Beer-Me-Up) - Beer Me Up is an iOS and Android app build with Flutter.

  The app is a personal beer logging that allows you to enter every beer you have to be sure to remember them forever.Beer Me Up is an iOS and Android app build with Flutter.

  The app is a personal beer logging that allows you to enter every beer you have to be sure to remember them forever.

- ![](https://img.shields.io/github/stars/MSzalek-Mobile/weight_tracker?style=social) [WeightTracker](https://github.com/MSzalek-Mobile/weight_tracker) - Simple application for tracking weight. See Google Play for more details about this app!

- ![](https://img.shields.io/github/stars/iampawan/AI-Radio?style=social)  [AI-Radio](https://github.com/iampawan/AI-Radio) - AI-Powered Voice Assistant Flutter Radio App

- ![](https://img.shields.io/github/stars/MDSADABWASIM/Toughest?style=social) [toughest](https://github.com/MDSADABWASIM/Toughest) - Interview questions and answers for preparation, built in pure flutter also have CI implementation for learning.

- ![](https://img.shields.io/github/stars/MDSADABWASIM/You?style=social) [You](https://github.com/MDSADABWASIM/You) - The app checks what internet knows about you.

- ![](https://img.shields.io/github/stars/Blakexx/CryptoTracker?style=social) [Platypus Crypto](https://github.com/Blakexx/CryptoTracker) - Platypus Crypto is an ad-free cross-platform robust solution for tracking cryptocurrency assets. Our intuitive interface includes real-time 7-day graphs, current prices and market caps, and percent change over time. Featuring rapid sort, search and refresh features, and support for 32 fiat currencies, Platypus Crypto enables casual and power users alike to monitor cryptocurrency assets on-the-go! Our customization options allow for the removal of 7-day graphs for a more compact feel and a dark theme.

- ![](https://img.shields.io/github/stars/PierreBresson/flutter-wordpress-podcast?style=social)  [Flutter Wordpress Podcast](https://github.com/PierreBresson/flutter-wordpress-podcast) -  🎤 Podcast white label app based on Wordpress API

## Contribution

Your contributions and suggestions are heartily welcome.

Thanks to all the people who already contributed!

<a href="https://github.com/nepaul/awesome-flutter/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=nepaul/awesome-flutter" />
</a>

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
