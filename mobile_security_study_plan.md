---
title: "Zero to Hero"
---

## Self-learning I. (2 weeks)
- **Main Learning material:** - [OWASP Mobile Security Testing Guide](https://mobile-security.gitbook.io/mobile-security-testing-guide)


## Onboarding I. IOS (~ 1 week)
- IOS fundamentals (architecture, jailbreaking, Objective-C, Swift, etc.)
    - [OWASP Mobile Security Testing Guide - iOS Testing Guide](https://mobile-security.gitbook.io/mobile-security-testing-guide/ios-testing-guide/0x06a-platform-overview)
- Tool installation
    - [fake AP](../../general/fakeap)
    - [grapefruit](https://github.com/ChiChou/grapefruit)
    - ~[passionfruit](../../ios/tools/passionfruit)~ (deprecated, only if you must use old Frida version on the device)
    - [Frida](../../ios/tools/frida)
    - Xcode
    - IOS App Signer
- Reporting - (General IOS issues showcase)
- Vulnerable Application hacking (choose one):
   - [DVIA V2](https://github.com/prateek147/DVIA-v2)
   - [WATF Bank](https://github.com/WaTF-Team/WaTF-Bank)
   - [UnCrackable Mobile Apps](https://github.com/OWASP/owasp-mstg/tree/master/Crackmes)
   - [OWASP IGOAT](https://github.com/OWASP/igoat)
- Frida IOS fundamentals
    - [Knowledgebase/IOS/Frida](../ios/tools/frida)
    - [CRS frida-scripts git repository](https://git.crs.lab/crs_projects/frida-scripts/-/tree/master/ios)
    - [frida-boot e-learning](https://www.youtube.com/watch?v=CLpW1tZCblo)

## Onboarding II. Android (~ 1 week)

- Android fundamentals (architecture, rooting, Java, etc.)
    - [OWASP Mobile Security Testing Guide - Android Testing Guide](https://mobile-security.gitbook.io/mobile-security-testing-guide/android-testing-guide/0x05a-platform-overview)
- Tool installation
    - [CRS Knowledgebase/Android Testing Tools Setup](../android/tools/An droid_testing_setup_for_macOS)
        - JADX
        - etc.
    - [Android Virtual Device (Emulator)](../ios/tools/avd)
    - [Frida](../android/tools/frida)
    - [Frida Server](../android/tools/frida)
- Reporting - (General Android issues showcase)
- Vulnerable Application hacking (choose one):
   - [DIVA Android](https://github.com/payatu/diva-android)
   - [WATF Bank](https://github.com/WaTF-Team/WaTF-Bank)
   - [UnCrackable Mobile Apps](https://github.com/OWASP/owasp-mstg/tree/master/Crackmes)
- Frida Android fundamentals
    - [Knowledgebase/Android/Frida](../../android/tools/frida)
    - [CRS frida-scripts git repository](https://git.crs.lab/crs_projects/frida-scripts/-/tree/master/android)
    - [frida-boot e-learning](https://www.youtube.com/watch?v=CLpW1tZCblo)

## Self-learning II. (~1-2 weeks)
- Go through more hand picked vulnerable apps (see above)

## Test (1 week)
- Pentesting a vulnerable app, and write report.
- TODO: Select the exact vulnerable app.
- TODO: CRS should develop an own vulnerable app in the future.
- Team lead will read the report and evaluate trainee's knowledge.

## Shadowing (1 IOS + 1 Android project) ~ 2 week

- All of the necessary tools should be installed **before** first day of shadow.
- Start with your favorite platform, then the second one should be much easier to learn.
- Deployment of application to the device: shadow learn.
- Following methodology in KB-Checklist.
- Use KB-Checklist for Testing Guide, and Knowledgebase for the tools.
- Use all of the tools: Frida, JADX, passionfruit, ssh.
- Reporting can be done by shadower.
- **Shadower time should not allocated on project!**
- Will learn to do minimum necessary tests. Can do basic IOS and Android apps alone.

## JUNIOR MOBILE PENTESTER
- At this point tester can do basic IOS and Android apps alone.
- Senior testers must help out with Frida hooks or testing advanced security features.
- Preferably junior tester is on the same project with more senior tester (e.g.: IOS: junior + Android: senior).
- Tester should be able to jailbreak/root phone and install and use various tools.

## Self-learning II. (~4 weeks)

- Prerequisites: learn to code (e.g. Python, JavaScript, Java, C++)
- Software architecture fundamentals:
    - OOP
    - Software architectures (MVVM, delegate, etc.)
    - Java
    - Native code, C standard libraries, Assembly
- Learn to code on iOS (Swift and Objective-C)
    - TODO: There are trainings, however still need to find a good training. Must ignore UI things, concentrate on application logic, networking and security features.
    - `TODO: Udacity IOS Nanodegree`
    - Develop sample application in Xcode with some security features
- Learn to code on Android
    - TODO: There are trainings, however still need to find a good training. Must ignore UI things, concentrate on application logic, networking and security features.
    - `TODO: Udacity Android Nanodegree`
    - Develop sample application in Android Studio with some security features
- Learn to code in JavaScript
- Introduce frameworks:
   - ionic
   - Cordova
   - React Native
- Binary training

## SENIOR MOBILE PENTESTER (HERO)
- At this point can work totally alone.
- Can answer complex questions about application security architecture.
- Can reverse engineer complex applications written in native code also.
- Frida expert.
- Can improve knowledge of team and himself through self-learning, teaching, research, development.
