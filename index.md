# Featured pet projects

## One With Language

I wrote O.W.L. as a part of my engineer's work while at Wrocław University of Technology. It is an application for Android meant for teaching a language from scratch (as the subject of the reasearch were modern means of e-learning via mobiles and such). It supports API 16+ by utilising the AppCompat library, therefore the device coverage it offers is large (99.9% according to the data provided by Google play with the timestamp of February 5th, 2018, which is larger than in June 2017 when the project was published).

In the abstract of the paper I wrote the following:
_The purpose of this work is to design a mobile application that allows remote teaching. Introduced the need for continued development and upgrading skills, as well as methods of satisfying it. Explained the concept of e-learning and how it is being implemented today, using the latest available technology. After analysing the existing solutions on the market in the category of mobile applications available for the Android platform, the scope of the task has been allotted. Further chapters describe the details of the design concept of the project – the implementation is built upon those foundations. Defined the functional and non-functional requirements and the structure of the system and its components have been analysed. A database schema and application interface screens have been designed. The implementation and related issues are discussed in detail in the penultimate chapter. The final chapter summarizes the work on the application and draws conclusions._
Unfortunately the rest of the document is only available in polish and I currently do not plan on translating it.

There are some features that ideally should be improved or added, however this was just one person's university project. Since the market is currently fairly saturated with apps of similar purpose, there is no need of further developing this project without having greater resources available at hand.

The application features several screens. The first one is a menu with buttons leading to different sections of the app.

![Main screen](http://stasis.eu/Android/images/sorted/1.png)

There is also a side navigation present, accessible from all screens via the hamburger icon.

![Side navigation](http://stasis.eu/Android/images/sorted/2.png)

One of the main sections is a dictionary - a list of words with corresponding pictures and example sentences. Upon first use the list needs to be populated from external database (the data is also saved locally for faster load times; if the version of the external database matches, no extra data would be downloaded).

![Populating database](http://stasis.eu/Android/images/sorted/3.png)
