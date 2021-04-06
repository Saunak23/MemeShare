# MemeShare
Memes are shared among Friends to give a smile in your counterpart's face. Share this witty , Pleasurable and Entertaining Memes to make their day.

<h2> Volley </h2>
Volley is an HTTP library that makes networking for Android apps easier and most importantly, faster. 

Volley offers the following benefits:

Automatic scheduling of network requests.

Multiple concurrent network connections.

Transparent disk and memory response caching with standard HTTP cache coherence.

Support for request prioritization.

Cancellation request API. You can cancel a single request, or you can set blocks or scopes of requests to cancel.

Ease of customization, for example, for retry and backoff.

Strong ordering that makes it easy to correctly populate your UI with data fetched asynchronously from the network.

Debugging and tracing tools.

Volley excels at RPC-type operations used to populate a UI, such as fetching a page of search results as structured data. It integrates easily with any protocol and comes out of the box with support for raw strings, images, and JSON. By providing built-in support for the features you need, Volley frees you from writing boilerplate code and allows you to concentrate on the logic that is specific to your app.

<h2> API:-</h2> An API is a set of programming instructions and standards for accessing a web tool or database. A software company releases its API to the public so other software developers can design products that are powered by its service. The API is usually packaged in an SDK.

<h3> API Call </h3>
Performing API call in Android is a little bit difficult because first, you need to check the internet connection. If it’s available then only you can make a request. And you need to handle the cache also.

To simplify these operations several popular Open Source libraries are available. The most popular ones are the following:

Volley
Retrofit

<h2>Library:-</h2> A library module is useful in the following situations:

When you're building multiple apps that use some of the same components, such as activities, services, or UI layouts.

When you're building an app that exists in multiple APK variations, such as a free and paid version and you need the same core components in both.

<h2> Android Progress Bar </h2>
Android ProgressBar is a graphical view indicator that shows some progress. Android progress bar displays a bar representing the completing of the task. Progress bar in android is useful since it gives the user an idea of time to finish its task.

Using a ProgressBar is a good user experience practice since it displays the status of progress of the given task (such as downloading an image) to the user.

Android ProgressBar attributes
Some important attributes used to describe a ProgressBar are given below.

**android:max :** We can set the maximum value of the ProgressBar using this attribute. By default the progress bar maximum value is 100.

**android:indeterminate :** A boolean value is set depending on whether the time is determinate or not. Setting this attribute to false would show the actual progress. Else if it’s set to true a cyclic animation is displayed to show that progress is happening.

**android:minHeight :** It’s used to set the height of the ProgressBar.

**android:minWidth :** It’s used to set the width of the ProgressBar.

**android:progress :** It’s used to set the number by which the progress bar value will be incremented.

**style :** By default the progress bar will be displayed as a spinning wheel. If we want it to be displayed as a horizontal bar, we need to set the attribute as : style=”?android:attr/progressBarStyleHorizontal”.

<h2> Glide Library </h2>
Glide is an Image Loader Library for Android developed by bumptech and is a library that is recommended by Google. It has been used in many Google open source projects including Google I/O 2014 official application. It provides animated GIF support and handles image loading/caching.

<h2> Singleton Class </h2>
If your application makes constant use of the network, it's probably most efficient to set up a single instance of RequestQueue that will last the lifetime of your app. You can achieve this in various ways. The recommended approach is to implement a singleton class that encapsulates RequestQueue and other Volley functionality. Another approach is to subclass Application and set up the RequestQueue in Application.onCreate(). But this approach is discouraged; a static singleton can provide the same functionality in a more modular way.

A key concept is that the RequestQueue must be instantiated with the Application context, not an Activity context. This ensures that the RequestQueue will last for the lifetime of your app, instead of being recreated every time the activity is recreated (for example, when the user rotates the device).
