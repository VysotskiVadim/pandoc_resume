Vadzim Vysotski
============

----

>  Software engineer since 2014.
>  Worked in different areas: backend, mobile cross-platform, game dev, native Android.
>  Fan of Test Driven Development and Agile. Team player. Mentor.

----

[+375 44 73 444 53](tel:+375447344453) \
vysotski.vadim@gmail.com \
Telegram: [vadzimv](https://t.me/vadzimv/) \
[vadzimv.dev](https://vadzimv.dev/)

Education
---------

2011-2016
:   **Specialist, Computer Science**; Belarusian State University of Informatics and Radioelectronics (Minsk)

Experience
----------

[Godel Technologies](https://www.godeltech.com/). 2019 - 2021.

Jobseeker app. 
:   Android application that helps people find and apply for a job.
    Can't share the link because of NDA.

    The new native application replaces the existing Xamarin app.
    The application is already available on Google Play.
    ~120K DAU. 99.91% Crash free.

    Used intensively: Kotlin, Clean Architecture, TDD, Coroutines, MVVM, Android Framework, Koin, Gradle, JUnit, Espresso, TDD, Android View Binding, Facebook screenshot tests, Firebase, Room, Auth0.
    
    Team size: 3 Android dev, 3 iOS, 1 backend.

    * Implemented infrastructure components that were used by the teammates: Authentication, Espresso Idling resources, Typesafe mock https server, View  screenshot tests for day/night mode, Network, Offline actions synchronization, Logs and crash reports. Implemented custom navigator for Jetpack navigation that supports show full-screen fragments and adding fragments.
    * Worked without QA. Tested teammates features;
    * Adopted additional layer to UI architecture that simplifies view screenshot testing by making it faster and more stable;
    * Reduced UI tests flakiness from 60% to 20%, i.e. only 1 of 5 runs gives you false-negative result;
    * Reviewed teammates' code and was reviewed. Aligned the Android team in used coding and architecture approaches;
    * Automated deployment to Google Play and Firebase so that every small change was delivered to internal testers with 0 effort;
    * Automated PR validation, so that develop branch was always green;
    * Facilitated Android team's meetings so that all 3 devs agreed with the technical directions; 
    * Worked with the backlog. Organized and led refinements. Split user stories to find less important parts and reduce the scope;
    * Adopted refinements led by developers, so that every team member was highly involved;
    * Owned technical backlog. Put technical tasks to a sprint at convenient moments, so that we were continuously improving tooling and approaches without affecting business values delivery.

[Playtika](https://www.playtika.com/). 2017 - 2019

Poker Heat game.
:   Texas Holdem poker mobile game. ~150k DAU. \
    [Google play](https://play.google.com/store/apps/details?id=com.bigblueparrot.pokerfriends&hl=en&gl=US)
    [App store](https://apps.apple.com/us/app/poker-heat-texas-holdem-poker/id480523695)
    [Facebook](https://apps.facebook.com/pokerheat/)

    Used intensively: Haxe, Monosyne (in-house game engine), TDD\
    Used less so: C#, JS, Gradle, Android, iOS

    * Implemented features that require synchronization of a few microservices, animations, and user actions. It's just tons of asynchronous code;
    * Split existing heavyweight screens into modules(module per feature), so that it's easy to: add/delete/change features, switch on/off features at runtime;
    * Adopted IoC container's scopes that simplified state management;
    * Supported company infrastructure libraries: fixed C# specific issues in Haxe code, setup unit tests to cover cs target;
    * Ported but not released the existing game for the Chinese market;
    * Implemented text localization mechanism based on code generation;
    * Setup web client CI;
    * Improved web client deployment process to support build per QA or more simultaneously, not just 4 stages as it was before;
    * Involved everybody in the release process, so we got rid of bus factor;
    * As a client developer negotiated with product guys incoming features, to find a perfect balance between technical complexity and business value.

[EPAM systems](https://www.epam.com/). 2014 - 2017

Coffee machine controller
:   Mobile application to control the brewer

    Used intensively: C#, Android, iOS, Xamarin.\
    Used less so: JS, Java

Customer host assistance
:   Mobile application for airport's host assistance to have info about flights and passengers

    Used intensively: C#, Android, iOS, Xamarin

ERP
:   Migration of the old ERP system from VBS HTML JS to new technology stack: ASP.NET MVC 4 + XSL-FO (for PDF generation) + Knockout.

    Used intensively: C#, XSLT, XSL-FO, T-SQL\
    Used less so: JS, Knockout


Other Experience
--------------------

Android Academy Minsk
:   One of Android Academy Minsk organizers.
    I'm in charge of organization and speak on some of our lectures.
    See the [videos](https://youtube.com/playlist?list=PLUxHOqbz8qZ2OL9QNU6A6pRP-Nmke3OyT)

Open Source
:   Added support of Android X Test Orchestrator for facebook screenshot library.
    [Pull Request](https://github.com/facebook/screenshot-tests-for-android/pull/264).

    Implemented [Visual Studio Code Xamarin Debugger](https://github.com/VysotskiVadim/vscode-xamarin-debug) in 2018.
    It's a forked mono debugger, with support of debugging mono runtime which is used in Xamarin.Android applications.
    It's the only tool, at least in 2018, which allows debugging Xamarin.Android from Linux machine.
