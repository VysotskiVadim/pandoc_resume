Vadzim Vysotski
============

----

>  Software engineer since 2014.
>  Worked in different areas: backend, mobile cross platform, game dev, native Android.
>  Fan of Test Driven Development and Agile. Team player. Mentor.

----

Contacts
--------
[+375 44 73 444 53](tel:+375447344453) \
vysotski.vadim@gmail.com \
Telegram: [vadzimv](https://t.me/vadzimv/) \
[vadzimv.dev](https://vadzimv.dev/)

Education
---------

2011-2016
:   **Specialist, Computer Science**; Belarusian State University of Informatics and Radioelectronics (Minsk)

    *Used intensively: C#, .NET\
    Less so: C, C++, JS, Java*

Experience
----------

**Job seeker app(2019-2021)**

Android application that helps people find and apply for a job. Hasn't been released yet, Alpha testing. 

Used intensively: Kotlin, Clean Architecture, TDD, Coroutines, MVVM, Android Framework, Koin, Gradle, JUnit, Espresso, TDD, Android View Binding, Facebook screenshot tests, Firebase, Room, Auth0.

* Took technical leadership in the team of 3 devs.
* Automated all the routine: deployment to firebase and google play, auto tests run, code style validation.
* Worked without QA. I was responsible for the quality of my code. Tested teammates features.
* Worked with the backlog. Organized and led refinements. Split user stories to find less important parts and reduce the scope.
* Implemented view screenshot tests for day and night mode.
* Sold to the team architecture that simplifies view screenshot testing.
* Reduced Espresso and screenshots tests flakiness from 60% to 20%, i.e. only 1 of 5 runs gives you false negative result. 

**Poker Heat game (2017-2019)**

Texas holdem poker mobile game. ~150k DAU.
[Google play](https://play.google.com/store/apps/details?id=com.bigblueparrot.pokerfriends&hl=en&gl=US)
[App store](https://apps.apple.com/us/app/poker-heat-texas-holdem-poker/id480523695)
[Facebook](https://apps.facebook.com/pokerheat/)

Used intensively: Haxe, Monosyne (in-house game engine), TDD\
Used less so: C#, JS, Gradle, Android, iOS

* Implemented features which requires synchronization of few microservices, animations and user actions: it's just a tons of asynchronous code;
* Improved project stability by refactoring which fixed ANR and crashes;
* Split existing heavyweight screens into modules(module per feature), so that it's easy to: add/delete/change features, switch on/off features at runtime;
* Setup IoC container's scopes;
* Did code review and was reviewed by teammates;
* Supported company infrastructure libraries: fixed C# specific issues in Haxe code, setup unit tests to cover cs target;
* Ported but not released existing game for Chinese market;
* Implemented text localization mechanism;
* Setup web client CI;
* Improved web client deployment process to support build per QA or more simultaneously, not just 4 stages as it was before;
* As a client developer negotiated with product guys incoming features, to find a perfect balance between technical complexity and business value.

**Coffee machine controller (2016-2017)**

Mobile application to control the brewer

Used intensively: C#, Android, iOS, Xamarin.\
Used less so: JS, Java

**Customer host assistance (2015)**

Mobile application for airport's host assistance to have info about flights and passengers

Used intensively: C#, Android, iOS, Xamarin

**ERP (2014-2015)**

Migration of the old ERP system from VBS HTML JS to new technology stack: ASP.NET MVC 4 + XSL-FO (for PDF generation) + Knockout.

Used intensively: C#, XSLT, XSL-FO, T-SQL\
Used less so: JS, Knockout


Other Experience
--------------------

Android Academy Minsk
:   Joined Android Academy Minks in 2019 as a mentor.
    Now I'm the member of the Org team.
    I'm in charge of organization and speak on some of our lectures.
    See the [videos](https://youtube.com/playlist?list=PLUxHOqbz8qZ2OL9QNU6A6pRP-Nmke3OyT)

Open Source
:   Added support of Android X Test Orchestrator for facebook screenshot library.
    [Pull Request](https://github.com/facebook/screenshot-tests-for-android/pull/264).

    Implemented [Visual Studio Code Xamarin Debugger](https://github.com/VysotskiVadim/vscode-xamarin-debug) in 2018.
    It's forked mono debugger, with support of debugging mono runtime which is used in Xamarin.Android applications.
    It's the only tool, at least in 2018, which allows debugging Xamarin.Android from Linux machine.
