# Android Development Setup Guide

## Introduction

This guide explains the complete setup process for starting Android development using Android Studio.

To build Android applications, we need:

* Android Studio
* Java Development Kit (JDK)
* Android SDK
* Gradle
* Git
* GitHub account

---

# Step 1: Install Android Studio

Android Studio is the official IDE for Android development.

### Steps:

1. Visit the official Android Studio website.
2. Download the installer.
3. Run the setup file.
4. Complete installation.

### Features of Android Studio:

* Code editor
* Emulator
* Debugging tools
* SDK Manager
* Layout editor

Installed successfully.

---

# Step 2: Install Java Development Kit (JDK)

JDK is required for compiling Java/Kotlin code.

### Steps:

1. Download JDK.
2. Install it.
3. Set environment variables.

### Check installation:

```bash
java -version
```

Expected output:

```bash
java version "17.x.x"
```

Purpose:

* Compile code
* Run Android apps

---

# Step 3: Install Android SDK

Android SDK contains tools for app development.

### Installed SDK Components:

* SDK Platform
* SDK Tools
* Platform Tools
* Build Tools

### Setup:

Open:
Android Studio → SDK Manager

Install:

* Latest Android SDK
* Emulator package

Purpose:

* Build and test applications

---

# Step 4: Configure Gradle

Gradle is the build system used in Android.

It manages:

* Dependencies
* Build process
* APK generation

Example:

```gradle
dependencies {
    implementation 'androidx.appcompat:appcompat:1.6.1'
}
```

Gradle sync completed successfully.

---

# Step 5: Set Up Emulator

Android Emulator is used for testing apps.

### Steps:

1. Open Device Manager
2. Create virtual device
3. Select device type
4. Select Android version
5. Finish setup

Emulator started successfully.

Purpose:

* Test app without physical phone

---

# Step 6: Install Git

Git is used for version control.

### Steps:

1. Download Git
2. Install Git
3. Configure Git

Commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

Check:

```bash
git --version
```

Purpose:

* Track project changes
* Push code to GitHub

---

# Step 7: Create GitHub Repository

GitHub is used to store project online.

### Steps:

1. Create GitHub account
2. Create new repository
3. Add README file

Repository created for internship tasks.

Purpose:

* Project submission
* Code backup
* Collaboration

---

# Step 8: Create First Android Project

Created first app:
**HelloWorldApp**

### Steps:

1. Open Android Studio
2. Click New Project
3. Select Empty Activity
4. Enter project name
5. Select language (Java/Kotlin)
6. Finish

Learned:

* Project structure
* MainActivity
* XML layouts

---

# Step 9: Run First Application

Connected emulator and ran app successfully.

Output:

* App launched successfully
* Displayed "Hello World"

Verified:

* Build successful
* App execution successful

---

# Tools Used

* Android Studio
* Java JDK
* Android SDK
* Gradle
* Git
* GitHub

---

# Outcome

Successfully completed Android development environment setup.

Achievements:
✔ Installed all required tools
✔ Configured development environment
✔ Created first Android project
✔ Learned project structure
✔ Connected emulator
✔ Ran application successfully

This setup is ready for further Android development learning.
