# News-portal

# News App
Project as a part of Android Basics Nanodegree at Udacity

### Project Overview

The goal is to create a News Feed app which gives a user regularly-updated news from the internet 
related to a particular topic, person, or location. 
In this project, use [Guardian API](http://open-platform.theguardian.com/documentation/). 
This is a well-maintained API which returns information in a JSON format.

### API Key Note
You need to insert your API key.
Go to a file named `Constants.java` and find the value of API_KEY.
Replace "test" with "YOUR-API-KEY".
```
public static final String API_KEY = "YOUR-API-KEY";
```

### Features

* Navigation Drawer
* Fragments
* ViewPager plus TabLayout
* Loaders
* Intent
* Guardian API
* JSON Parsing
* Glide
* CardView
* RecyclerView
* SharedPreferences


I built the **Guardian NewsFeed** app from scratch. I made use of the design of my News app one of the Android Basics Nanodegree projects, which is on this GitHub, but the code is different from my News app. I added the podcast feature which allows you to stream the guardian podcasts for free.

The differences are as follows.
*	Use the Paging library to load news data gradually and gracefully, so that you do not need to adjust the Number of Items in the Settings
*	Search articles by keyword
*	Add Podcast section. You can listen to Guardian podcasts anywhere, anytime for free, add favorite episodes, download episodes for offline listening
*	Use Constraint layout which allows you to make complex layouts with a flat view hierarchy
*	Use Third-party libraries – Android Architecture Components, Android Data Binding, Retrofit, Gson, OkHttp, ExoPlayer, Glide, Glide Transformations, SimpleXmlConverter, Timber, Firebase Analytics, Crashlytics
*	Replace Toast message with SnackBar message
*	Minimum SDK is 16, Android 4.1 (JELLY_BEAN)
*	Add the launcher icon that I created
