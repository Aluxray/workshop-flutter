# Workshop Flutter

## Develop an Android app with Flutter

Hello,

Welcome to this Flutter workshop. Today you will learn how to create your own Android app with Flutter.

## What is Flutter?

Flutter is a framework using the programming language Dart to build front side applications.

[Dart documentation to understand the basics](https://dart.dev/language)

The language is very similare to C and Python so you shouldn't feel lost, however, if you have issues with the language itself, even after checking the link above, don't hesitate to call the organisers for help!

## Setup Flutter on your machine

The setup of **Flutter** is quite tricky and long, but you need everything to be installed and ready to start doing the workshop. Go check the **[Setup Guide](./Setup.md)** for **Flutter** before starting.

## Exercise 0

- Now that everything is set up, we can finally get into the real deal: making our first **Android app with Flutter**!
- We will assume that you are using **Android Studio** for the sake of this workshop, but don't hesitate to go check the optional 5th step of the **[Setup Guide](./Setup.md)**, to set up the project with **VS Code**
- Launch **Android Studio** and select `New Flutter Project`. Your **Flutter SDK** should already be selected as `/usr/bin/flutter`, if not, run `flutter doctor` and see if **Android Toolchain** is green. Click `Next`.
- Name your project however you like (name it `workshop_flutter` if you have no idea what to put) and select the directory you created for this workshop as the project location. `Kotlin` and `Swift` should be selected for **Android language** and **iOS language** respectively; and only check the `Android` box (we don't need the other plateforms for this workshop, but you can keep them if you don't mind wasting space on your disk). Click `Create`.
- Select your **Android emulator** or your **Android device** in the top right hand corner to indicate on which plateform to launch the program.
<br/>
<br/>
![Select device](./readme-assets/select_device.png)
<br/>
- Now hit `Run` and you'll have started your very first **Flutter Android app**!
