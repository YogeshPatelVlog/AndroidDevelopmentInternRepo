# Android Basics

## Introduction

Android is an open-source operating system developed by Google for smartphones, tablets, and other devices. It is widely used for mobile application development.

Android applications are mainly developed using **Java** or **Kotlin** in **Android Studio**.

---

# Core Components of Android

## 1. Activity

An **Activity** represents a single screen in an Android app.

For example:

* Login Screen
* Home Screen
* Profile Screen

It controls user interaction.

### Activity Lifecycle:

* **onCreate()** → Called when activity is created
* **onStart()** → Activity becomes visible
* **onResume()** → Activity starts interacting with user
* **onPause()** → Activity partially hidden
* **onStop()** → Activity completely hidden
* **onDestroy()** → Activity destroyed

Example:

```java
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_main);
}
```

---

## 2. Fragment

A **Fragment** is a reusable part of an Activity.

Used for:

* Navigation
* Multiple screen sections
* Reusable UI

Advantages:

* Better code organization
* Reusability
* Dynamic UI updates

---

## 3. Layouts

Layouts are used to design app UI.

### Types of Layouts:

### LinearLayout

Arranges elements in:

* Vertical
* Horizontal

Example:

```xml
<LinearLayout
    android:orientation="vertical">
</LinearLayout>
```

---

### RelativeLayout

Positions elements relative to each other.

Example:
Button below TextView.

---

### ConstraintLayout

Most flexible and modern layout.

Benefits:

* Better performance
* Complex UI design

---

### FrameLayout

Used to display one element at a time.

Mostly used with fragments.

---

## 4. Views

Views are UI components.

Examples:

* TextView
* Button
* EditText
* ImageView

Example:

```xml
<Button
    android:text="Click Me"/>
```

---

## 5. Intent

Intent is used to communicate between activities.

### Types:

### Explicit Intent

Used to open a specific activity.

Example:

```java
Intent intent = new Intent(MainActivity.this, SecondActivity.class);
startActivity(intent);
```

---

### Implicit Intent

Used to perform actions like:

* Open browser
* Open camera

---

## 6. AndroidManifest.xml

This file stores app information:

* App name
* Activities
* Permissions

Example permissions:

* Internet
* Camera
* Storage

---

## 7. Gradle

Gradle is a build automation tool.

Used for:

* Managing dependencies
* Building APK
* Running app

Example dependency:

```gradle
implementation 'androidx.appcompat:appcompat:1.6.1'
```

---

## 8. RecyclerView

RecyclerView is used to display large lists efficiently.

Example:

* Contact list
* Product list

Advantages:

* Better performance
* View recycling

---

## 9. Toast

Toast shows short messages.

Example:

```java
Toast.makeText(this, "Hello", Toast.LENGTH_SHORT).show();
```

---

## 10. XML

XML is used for UI design in Android.

Used for:

* Layout design
* Styling

Example:

```xml
<TextView
    android:text="Welcome"/>
```

---

# Conclusion

Android development mainly depends on:

* Activities
* Fragments
* Layouts
* Views
* Intents
* Gradle
* Manifest

These basics are important for building Android applications.
