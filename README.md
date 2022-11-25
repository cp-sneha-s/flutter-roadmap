
<h1 align="center">Flutter Developer Roadmap 2022</h1>

![alt text](https://github.com/cp-sneha-s/flutter-roadmap/blob/main/flutter-roadmap-image.png)

Flutter Developer Roadmap 2022 is a learning path to understand flutter development.

## What is Flutter?

Flutter is an SDK(Software Development Kit) developed by google that allows developer to build native cross-platform apps with just one programming langauage-Dart. From single codebase, it creates native app for ios, Android and web, that can be published to the stores later.

# Table of Contents:
- [Sprint 1](https://github.com/cp-sneha-s/flutter-roadmap#sprint-1)
- [Sprint 2](https://github.com/cp-sneha-s/flutter-roadmap#sprint-2)
- [Sprint 3](https://github.com/cp-sneha-s/flutter-roadmap#sprint-3)
- [Sprint 4](https://github.com/cp-sneha-s/flutter-roadmap#sprint-4)
- [Sprint 5](https://github.com/cp-sneha-s/flutter-roadmap#sprint-5)
- [Sprint 6](https://github.com/cp-sneha-s/flutter-roadmap#sprint-6)

#### Let's start with basic learning.

## Sprint 1:

### Flutter basics:
* introduction to [Flutter](https://www.javtpoint.com/flutter)
* [Why flutter?](https://medium.com/flutter-community/reasons-why-flutter-is-setting-the-trend-in-mobile-app-development-4aa707532fb)
* [Set up](https://docs.flutter.dev/get-started/install)

### Dart basics:
* Introduction to [Dart](https://hackernoon.com/why-flutter-uses-dart-dd635a054ebf)
* [Dart](https://dart.dev/guides/language/language-tour) programming langauage

### Code style:
* [Best practices and tips](https://medium.com/flutter-community/flutter-best-practices-and-tips-7c2782c9ebb5)
* [Effective Dart](https://dart.dev/guides/language/effective-dart)
* [Flutter code formatting](https://docs.flutter.dev/development/tools/formatting)

#### Practicle 1.1
* Do all [Practicles](https://github.com/cp-sneha-s/flutter-roadmap/blob/main/Practical-1.1) using [Dartpad](https://www.dartpad.dev/?).

#### Practicle 1.2
* Create repository of practicle 1.1 on Gitlab

#### References
* Introduction to version control: [What Is Version Control?](https://tutorials.codebar.io/version-control/introduction/tutorial.html)
* How to use git
    -  [Version control with git](https://www.udacity.com/course/version-control-with-git--ud123)
    -  [Git: The Beginner's Guide to Understanding Core Version Control Concepts](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/10929402#overview)
    -  [When to commit in version control](https://softwareengineering.stackexchange.com/questions/74764/how-often-should-i-do-you-make-commits)
 
 ### Flutter Tools:
* [Hot Reload](https://docs.flutter.dev/development/tools/hot-reload)
* [Punspec file](https://docs.flutter.dev/development/tools/pubspec)

## Sprint 2:

* Introduction to [Declarative UI](https://docs.flutter.dev/get-started/flutter-for/declarative)
* Introduction to [Widgets](https://docs.flutter.dev/development/ui/widgets-intro)
* [Layouts in flutter](https://docs.flutter.dev/development/ui/layout)
* [Building Layout](https://docs.flutter.dev/development/ui/layout/tutorial)

### Supporting different devices
* [Adaptive and Resposive](https://docs.flutter.dev/development/ui/layout/adaptive-responsive) apps

### DelightFul User experience
* Intorduction to [Material components](https://docs.flutter.dev/development/ui/widgets/material)
* How to Build Beautiful UIs with Flutter Widgets 
    -  Udemy Course 1 - Section 6


### Practical 2.1
* Create given [Responsive UI](https://user-images.githubusercontent.com/92501869/202130578-6c42048a-ce47-4833-bdc2-9e700cc6a489.png)
   - You can use alternative images.
   
### Navigation:
* [Navigation](https://medium.com/easyread/3-options-for-creating-responsive-layouts-in-flutter-app-live-demo-68b0c0e955ab) in Flutter
* [Navigation and Routing](https://docs.flutter.dev/development/ui/navigation)
* Introduction to [Navigator 2.0](https://blog.codemagic.io/flutter-navigator2/)

### Practical 2.2
* Implement an app with a bottom bar that has 4 screens (home, setting, like, search).
   -  Implement a route between screens.
   - Implement Navigator 2.0
   
## Sprint 3:

### Json serialization:
* [Json and serialization](https://docs.flutter.dev/development/data-and-backend/json)
   - [Parsing Json](https://medium.com/@abhishekdoshi26/parsing-json-in-flutter-7519293f5168) in flutter
* [Auto generate](https://medium.flutterdevs.com/automatic-generate-json-serializable-in-flutter-4c9d2d23ed88) json serializable in flutter

### Networking:
* [Networking in flutter](https://docs.flutter.dev/development/data-and-backend/networking)
* [Retrofit](https://medium.com/mindful-engineering/retrofit-the-easiest-way-to-call-rest-apis-is-flutter-fe55d1e7c5c2)
* [Dio](https://pub.dev/packages/dio)-  powerful HTTP client of dart
* [Chopper](https://pub.dev/packages/chopper)- HTTP client generator for Dart and Flutter using source_gen and inspired by Retrofit.

### Practical 3.1
* Implement Food Application with following functionality 
* Fetch food feeds from API 
* User should be navigate to its detail page by clicking reciepe
* Add log click delete functionality on food click to delete food from local storage
* Implement [pull to refresh](https://pub.dev/packages/pull_to_refresh) functionality to refresh cached feeds in local storage.

    API - GET request - 'https://spoonacular-recipe-food-nutrition-v1.p.rapidapi.com/food/ingredient
    
    headers: {
    'X-RapidAPI-Key': '6991e41207mshaaf1e8dd61f03fdp17fbe9jsn3c96953146c7',
    'X-RapidAPI-Host': 'spoonacular-recipe-food-nutrition-v1.p.rapidapi.com'
  }
  * Note:
    - Use http package for networking
  
 ### Reference:
 * [Networking like a pro](https://medium.com/swlh/how-to-do-networking-like-a-pro-in-flutter-7e2612103cb5)
 * Flutter networking [tutorial](https://www.kodeco.com/5896601-flutter-networking-tutorial-getting-started)
 
 ### Work in background
 * [Concurrency](https://dart.dev/guides/language/concurrency) in Dart
 * [Asynchronous programming](https://dart.dev/codelabs/async-await)
 #### Reference:
 * [Asynchronous](https://medium.flutterdevs.com/concurrency-in-dart-b9171278af31) in Dart
 * [WorkManager](https://pub.dev/packages/workmanager)
 * [Thread and Isolate](https://medium.com/flutter-community/thread-and-isolate-with-flutter-30b9631137f3)
 
 ## Sprint 4:
 
 ### App Architecture:
 * [Archtectural overview](https://docs.flutter.dev/resources/architectural-overview)
 * [Flutter MVVM Architecture](https://medium.com/flutterworld/flutter-mvvm-architecture-f8bed2521958)
 * [MVVM](https://medium.flutterdevs.com/design-patterns-in-flutter-part-3-mvvm-a310de4eb83) design pattern
 
 ### State management:
 * [Interoduction](https://docs.flutter.dev/development/data-and-backend/state-mgmt/intro) to state management
 * [Conceptual types of state](https://docs.flutter.dev/development/data-and-backend/state-mgmt/ephemeral-vs-app)
 * State management [approaches](https://docs.flutter.dev/development/data-and-backend/state-mgmt/options)
 * Udemy Course 1: Section 16

### Local storage:
* [Store key-vaue pair](https://docs.flutter.dev/cookbook/persistence/key-value)
* [Read and wirte files](https://docs.flutter.dev/cookbook/persistence/reading-writing-files)
* [Sqlite database](https://docs.flutter.dev/cookbook/persistence/sqlite)

### Practical 4.1
* Create simple TODO app with CRUD operation with SQLite.
* Home screen should have list of task with add new task fab button.
* On the click of task it should be redirect to task status screen where it can be edit.
* On the cell swipe it shows delete option and on it's click that particular task should delete.
* Add option to active and inactive task.
  - Note
    - Use flutter bloc for state management
    - Use provider for state management
   
   
 ### Reference:
* [Database concepts](https://www.tutorialspoint.com/flutter/flutter_database_concepts.htm) in flutter
* [Provider](https://medium.com/codechai/provider-state-management-in-flutter-d453e73537c5)state management in flutter
* [BLoC](https://blog.logrocket.com/state-management-flutter-bloc-pattern/) state management in flutter

## Sprint 5

### Testing:
* [Intruduction](https://docs.flutter.dev/testing) to testing flutter apps
* [Unit testing](https://docs.flutter.dev/cookbook/testing/unit/introduction)
* [Widget testing](https://docs.flutter.dev/cookbook/testing/widget/introduction)
* [Integration testing](https://docs.flutter.dev/cookbook/testing/integration/introduction)
* Mock dependencies using [Mockito](https://docs.flutter.dev/cookbook/testing/unit/mocking)
* Introduction to [TDD](https://medium.com/upday-devs/flutter-test-driven-development-e57f2defff43)

### Package
* [Test](https://pub.dev/packages/test)

### Practical 5.1:
* Add Unit,widget and integration test in practical 4.1

### Depenedecy Injection
* [Introduction](https://www.geekyants.com/blog/understanding-dependency-injection-in-flutter-using-provider-143/) to dependency injection
* [DI in flutter](https://medium.com/flutter-community/flutters-dependency-injection-c4f053e4408)
* Package:
   -  [injectable](https://pub.dev/packages/injectable)
   -  [getIt](https://pub.dev/packages/get_it)

### Reactive programming
* [RxDart](https://pub.dev/packages/rxdart)
* Introduction to [RxDart](https://medium.com/flutter-community/why-use-rxdart-and-how-we-can-use-with-bloc-pattern-in-flutter-a64ca2c7c52d)

### Dev Tools:
* [Flutter Inspector](https://docs.flutter.dev/development/tools/devtools/inspector)
* [Memory allocation](https://docs.flutter.dev/development/tools/devtools/memory)
* Flutter performance [best practices](https://docs.flutter.dev/perf/best-practices)

## Sprint 6:

### Final Practice:
1 Implement a shopping application 
      
  Screen one - Home screen 
   -  On main screen show list of products - [API](https://fakestoreapi.com/products)
      
   -  Open product detail on it’s click - [API](https://fakestoreapi.com/products/1)
      
   -  Add option to search products by categories - [API](https://fakestoreapi.com/products/categories)
      
   -  Add option to check out all product in cart
 
  Screen two - Detail screen
   -  Show full detail with images and description 
   -  Add option to add/remove the product from the cart ( Add/delete an item in local database)  

  Screen three - Show products from cart
     
   -   Fetch and show all cart item from local database
   -   Add option checkout and show total price of products
   -   Add option to remove from cart
                  

  Screen four - Login 
   -   User must have to login before adding any item into cart - API
   -   Add option to logout 
      


  - Add unit test for all viewmodel and helper classes

 2  Make a calculator application. Save calculation history in the database. Users can view history and clear history.













