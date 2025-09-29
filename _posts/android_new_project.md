---
title: "Android - Creating a new project"
excerpt: "To start creating applications for Android, we first need to create a new project."
coverImage: "/assets/blog/android_new_project/android_studio_newprojectdialog.png"
date: "2025-09-29T22:13:00.000Z"
author:
  name: Isaiah Noel P. Salazar
  picture: "/assets/blog/authors/isaiah_noel_p_salazar.jpg"
ogImage:
  url: "/assets/blog/android_new_project/android_studio_newprojectdialog.png"
---

To start creating applications for Android, we first need to create a new project.

There will be a button available at the top of the starting page of Android Studio named "New Project".

<img style="border: solid black 1px;" alt="Android Studio New Project Button" src="https://i.ibb.co/HDmqyTGG/android-studio-newprojectbutton.png">

Creating a new project in Android Studio may be confusing for some people because of the multiple options given to us at the start.

<img style="border: solid black 1px;" alt="Android Studio New Project Dialog" src="https://i.ibb.co/4nyr5Qm0/android-studio-newprojectdialog.png">

To keep things simple, we can start with the "Empty Views Activity" option

<img style="border: solid black 1px;" alt="Android Studio Empty Views Option" src="https://i.ibb.co/Dfq3SvSY/android-studio-emptyviews.png">

Do note that other versions of Android Studio may not include this option.

For that scenario, we can simply pick the "No Activity" option.

<img style="border: solid black 1px;" alt="Android Studio No Activity Option" src="https://i.ibb.co/Zz1YK69p/android-studio-noactivity.png">

After clicking next, we can then edit a few details of the project such as:

The name

<img style="border: solid black 1px;" alt="Android Studio Project Name" src="https://i.ibb.co/RTkGcRsw/android-studio-name.png">

The package name

<img style="border: solid black 1px;" alt="Android Studio Project Package Name" src="https://i.ibb.co/7tXwwCnR/android-studio-packagename.png">

The save location of the project

<img style="border: solid black 1px;" alt="Android Studio Project Save Location" src="https://i.ibb.co/LX10JBMB/android-studio-savelocation.png">

The programming language the project will use

<img style="border: solid black 1px;" alt="Android Studio Project Programming Language" src="https://i.ibb.co/Ps9vTs9z/android-studio-language.png">

The minimum Android version the project (or the application) support

<img style="border: solid black 1px;" alt="Android Studio Project Android Version" src="https://i.ibb.co/PZs98WDY/android-studio-androidversion.png">

And the build configuration language of the project.

<img style="border: solid black 1px;" alt="Android Studio Project Build Configuration Language" src="https://i.ibb.co/hRC9Cd00/android-studio-buildconfiglanguage.png">

For now, we are going to be using these settings below:

<img style="border: solid black 1px;" alt="Android Studio Project Settings" src="https://i.ibb.co/Rkvk0CK7/android-studio-mydefault.png">

Upon clicking the "Finish" button, you will see this window pop up.

<img style="border: solid black 1px;" alt="Android Studio IDE" src="https://i.ibb.co/B59rDs3J/android-studio-idestart.png">

Do note that you will need to let the IDE finish the Gradle project sync indicated near the top,

<img style="border: solid black 1px;" alt="Android Studio Gradle Sync at the Top" src="https://i.ibb.co/d0vS53Gc/android-studio-gradlesynctop.png">

and at the bottom of the window.

<img style="border: solid black 1px;" alt="Android Studio Gradle Sync at the Bottom" src="https://i.ibb.co/HTnP3SNS/android-studio-gradlesyncbottom.png">

After the Gradle has finished syncing, this will be the final look of the IDE.

<img style="border: solid black 1px;" alt="Android Studio IDE Final Look" src="https://i.ibb.co/rKTJ26V5/android-studio-idefinal.png">

Do note that if you chose the "No Activity" option, you will not have the default "activity_main.xml" and "MainActivity.java" files at the start.

<img style="border: solid black 1px;" alt="Android Studio No Activity IDE Final Look" src="https://i.ibb.co/9mMW4yBN/android-studio-noactivityidefinal.png">

To add a new activity, right-click on the "app" folder on the left and choose the "New > Activity > Empty Views Activity" option.

<img style="border: solid black 1px;" alt="Android Studio No Activity New Activity" src="https://i.ibb.co/23wz1P1T/android-studio-noactivitynewactivity1.png">

You can choose to either change or ignore the settings on the pop-up window.

<img style="border: solid black 1px;" alt="Android Studio No Activity New Activity Settings" src="https://i.ibb.co/N2n7VHBZ/android-studio-noactivitynewactivity2.png">

After clicking the "Finish" button, make sure to edit the "AndroidManifest.xml" located at the folders at the left at "app > manifests > AndroidManifest.xml" and modify the "\<activity\>" tag for the Activity you just created just like this example below.

<img style="border: solid black 1px;" alt="Android Studio No Activity Manifest" src="https://i.ibb.co/LX8SR4zn/android-studio-noactivitynewactivity3.png">

This will serve as the default activity that will open as soon as your application starts.