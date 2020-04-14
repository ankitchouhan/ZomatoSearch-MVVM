# ZomatoSearch-MVVM
[![Kotlin Version](https://img.shields.io/badge/kotlin-1.3.71-blue.svg)](http://kotlinlang.org/)

A restaurant searching app built with Android Jetpack.

Sample app which uses zomato search api to find restaurants and built to illustrate best development practices with Android Jetpack.

Libraries Used
---------------

* [Data Binding][1] - Declaratively bind observable data to UI elements.
* [LiveData][2] - Build data objects that notify views when the underlying database changes.
* [Navigation][3] - Handle everything needed for in-app navigation.
* [ViewModel][4] - Store UI-related data that isn't destroyed on app rotations. Easily schedule
     asynchronous tasks for optimal execution.
* [Glide][5] for image loading
* [Kotlin Coroutines][6] for managing background threads with simplified code and reducing needs for callbacks
* [Retrofit][7] Type-safe HTTP client for Android and Java
  
[1]: https://developer.android.com/topic/libraries/data-binding/
[2]: https://developer.android.com/topic/libraries/architecture/livedata
[3]: https://developer.android.com/topic/libraries/architecture/navigation/
[4]: https://developer.android.com/topic/libraries/architecture/viewmodel
[5]: https://bumptech.github.io/glide/
[6]: https://kotlinlang.org/docs/reference/coroutines-overview.html
[7]: https://square.github.io/retrofit/

Android Studio IDE setup
------------------------
* Use the latest version of Android Studio.
* (Optional) Currently app uses [ktlint](https://ktlint.github.io/) to enforce Kotlin coding styles.
* **Add your Zomato API Key in `Constants.kt` file to make search work.**

Discussions
-----------
If you've found an error in this sample, please file an issue: https://github.com/ankitchouhan/ZomatoSearch-MVVM/issues
