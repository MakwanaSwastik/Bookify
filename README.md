# Bookify

Bookify is an Android mobile application developed in Kotlin that provides users with a seamless PDF book reading experience. It offers a range of features to enhance reading and navigation within PDF documents, leveraging modern API integrations for robust performance and a user-friendly interface.

[![Download Bookify](https://img.shields.io/badge/Download-Bookify-blue.svg)](https://github.com/MakwanaSwastik/Bookify/raw/master/app/Bookify.apk)

## Features

- **Bookmarking:** Save your place in any PDF to easily return to it later.
- **Text Highlighting:** Highlight important text for quick reference.
- **In-document Search:** Quickly find specific text within a PDF.
- **Smooth Performance:** Optimized for a seamless reading experience.

## Dependencies

Below are the dependencies used in the Bookify project:

```groovy
plugins {
    id 'com.android.application'
    id 'org.jetbrains.kotlin.android'
    id 'kotlin-kapt'
    id 'com.google.gms.google-services'
}



implementation "com.airbnb.android:lottie:6.1.0"
implementation 'com.github.bumptech.glide:glide:4.15.1'

def lifecycle_version = "2.5.1"
implementation "androidx.lifecycle:lifecycle-viewmodel:$lifecycle_version"
implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:$lifecycle_version"

implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.6.4'

// Firebase Libraries
implementation platform('com.google.firebase:firebase-bom:32.2.0')
implementation 'com.google.firebase:firebase-analytics-ktx'
implementation 'com.google.firebase:firebase-database-ktx'
```

## Learning Resources

### Download Manager

- [Medium - Downloading File Properly in Android](https://medium.com/@aungkyawmyint_26195/downloading-file-properly-in-android-d8cc28d25aca)
- [Android Developer - DownloadManager](https://developer.android.com/reference/android/app/DownloadManager)
- [Android Developer - DownloadManager.Query](https://developer.android.com/reference/android/app/DownloadManager.Query)
- [Android Developer - DownloadManager.Request](https://developer.android.com/reference/android/app/DownloadManager.Request)

### Cursor

- [Android Developer - Cursor](https://developer.android.com/reference/android/database/Cursor)
- [Introduction to Cursor in Android](https://www.edureka.co/blog/introduction-to-cursor-in-android/)

### Nested RecyclerView

- [Optimizing Nested RecyclerView](https://proandroiddev.com/optimizing-nested-recyclerview-a9b7830a4ba7)
- [Medium - Nested RecyclerView in Android](https://medium.com/nerd-for-tech/nested-recyclerview-in-android-e5afb2b9771a#:~:text=Let%E2%80%99s%20talk%20about%20Optimizations%20of%20RecyclerView)

### Spring Animation

- [Android Developer - Spring Animation](https://developer.android.com/develop/ui/views/animations/spring-animation)
- [Medium - Spring Back RecyclerView: The Basics](https://medium.com/swlh/spring-back-recyclerview-the-basics-beebe3477cad)
- [GitHub - Android Animation Samples](https://github.com/KaustubhPatange/android-animation-samples)

### Stack Overflow

- [Stack Overflow - Android Studio Says Duplicate Class Found](https://stackoverflow.com/questions/75239367/android-studio-says-duplicate-class-found)

### GitHub

- [GitHub - FlutterEbookApp](https://github.com/JideGuru/FlutterEbookApp/tree/master)
- [GitHub - SpringScrollHelper.kt](https://github.com/KaustubhPatange/android-animation-samples/blob/master/SpringBack-RecyclerView/app/src/main/java/com/kpstv/dampingrecyclerview/ui/helpers/SpringScrollHelper.kt)

These resources provide valuable insights and guidance for developing various features and functionalities within the Bookify application.
