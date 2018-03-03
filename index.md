# Featured pet projects

## One With Language

I wrote O.W.L. as a part of my engineer's work while at Wrocław University of Technology. It is an application for Android meant for teaching a language from scratch (as the subject of the reasearch were modern means of e-learning via mobiles and such). It supports API 16+ by utilising the AppCompat library, therefore the device coverage it offers is large (99.3% according to the data provided by Google play with the timestamp of February 5th, 2018, which is larger than in June 2017 when the project was published).

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

Once the list was loaded, a random word was featured in the first tab. It was meant to rotate daily, but I believe the idea has been forgotten in the development progress and for now the word is chosen when the activity is (re)created.

![First tab](http://stasis.eu/Android/images/sorted/4.png)

In the second tab there is a list populated with all words from the database available in the given language (there actually were multiple implemented, as well as interface languages!).

![Second tab](http://stasis.eu/Android/images/sorted/5.png)

Clicking on an item from the list opens up a view with the details of the word - a picture with examples of use. 

![Item detail view](http://stasis.eu/Android/images/sorted/9.png)

Another section contains a list lessons available for the given language. Similarly to the dictionary list, clicking on a tile with lesson opens up the full lesson.

![Lessons](http://stasis.eu/Android/images/sorted/6.png)

Currently implemented lessons are rather plain, they can hold pictures, audio and even video, but unfortunately at the time of the app I did not own educational material that would include those. The current ones are a courtesy of a former german teacher at the university (retired by now).

![Lesson detail](http://stasis.eu/Android/images/sorted/7.png)

Another thing that the app allows is storing words or lessons in a list of favourites that is stored locally. The behaviour of the list is the same as in dictionary or lessons.

![Favourites](http://stasis.eu/Android/images/sorted/8.png)

The last section are tests of the language. Currently only quizes with either single choice or multiple choice are supported. First tab features achieved scores, if any are present, second lists the available tests.

![Tests](http://stasis.eu/Android/images/sorted/14.png)

Quizes have introduction, can support any amount of questions and possible answers. The amount of answers and correct answers depends on the question itself. The picture below displays a reading comprehension quiz:

![Test introduction](http://stasis.eu/Android/images/sorted/11.png)

Each question is displayed on a separate page, I found that a better solution than infinite scrolling.

![Test question](http://stasis.eu/Android/images/sorted/10.png)

At the end of the quiz the achieved result is shown.

![Test result](http://stasis.eu/Android/images/sorted/12.png)

The app also has a functional setting screen. It has some graphic issues, because official PreferenceCompat libraries are full of bugs that Google never fixed rather than making the problem irrelevant by obsolescence (a lot of devs target Lollipop and above (21+) these days. There are some open source bug fixes available, but they focused on the most critical issues.

![Settings](http://stasis.eu/Android/images/sorted/13.png)

## More at some undefined point in the future!

