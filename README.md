#Activity Spy

INFO 498 Android Development | Homework 3

Description:

* You need to build an app that knows how to write out to the Android diagnostic log on every Activity lifecycle method. It should run on IceCreamSandwich.
* Package it as "edu.washington.<yourNetID>.activityspy"

Stories

* As a user, when I launch the application, it should display “Greetings, UW!"
* As a developer, when I launch the application, it should write “on{event-name} event fired” to the INFO level of the diagnostic log for this application. If there is additional data with that event, it should also be written to the log.
* As a developer, when I close the application, it should write “We’re going down, Captain!” to the ERROR level of the diagnostic log in response to the onDestroy event.

Grading

* All your code should be in a GitHub repo under your account
    * repo should be called 'activityspy'
    * repo should contain all necessary build artifacts (remove gradle/ from .gitignore)
* include a directory called "screenshots", including:
    * screenshot of app running on emulator
    * pic or screenshot or movie of app running on a device
    * text-file contents of diagnostic log ('diagnostic.txt') after a run
