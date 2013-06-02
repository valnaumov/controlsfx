ControlsFX is an [open source project][1] for JavaFX that aims to provide really high quality UI controls and other tools to complement the core JavaFX distribution. It has been developed for JavaFX 8.0 and beyond, and has a guiding principle of only accepting new controls / features when all existing code is at an acceptably high level, including thankless jobs like having high quality javadoc documentation. This ensure a high quality release is available at all times, with all experimental work being done in branches of the main code base.

## Features

ControlsFX 8.0.0 will include the following features:

#### ButtonBar
**A horizontal container for buttons, which automatically places the buttons in the correct position for the underlying operating system. Just annotate the buttons with their type and itll handle the rest!

![ButtonBar][2]

* * *
#### Dialogs
A collection of pre-built, modal dialogs providing a really simple yet powerful API. Supports all manner of pre-built dialogs, and even allows for custom dialogs to be easily created.

![Dialogs][3]

* * *

#### GridView
A fast, virtualised grid container similar to ListView, except that there can be multiple cells on each row. Great for showing images!

![GridView][4]

* * *

#### RangeSlider
When you want a user to specify a range, right now you need to give them two text fields to type into (or two sliders). Yuck! This control is essentially the standard JavaFX slider but with two draggable thumbs on it one representing the low value and the other the high value. Much better!

![RangeSlider][5]

* * *

#### Rating
** A simple control that allows users to specify a rating between zero and a maximum value. This control supports partial ratings and updating on hover or on click.

![Rating][6]

* * *

#### SegmentedButton
When you have a ToggleGroup with buttons in it, it looks nicer when the buttons are grouped together (rather than individual buttons). This is exactly what the SegmentedButton control does it merges together all of your buttons in a ToggleGroup so that it is clear to users that the buttons are related.

![SegmentedButton][7]

* * *

**Important note: **ControlsFX will only work on JavaFX 8.0 b87 or later. If you are running on earlier versions of JDK 8, please [upgrade][8]. If you are still using JavaFX 2.x then unfortunately this library will not work for you.

### Getting Started

If you want to **play with** the ControlsFX sample application, either clone the ControlsFX repo from bitbucket and then run the [org.controlsfx.HelloControlsFX][10] application that resides within the [src/samples/java][11] directory, or run the samples jar file from the command line with the following command (or a variation depending on your operating system):

java -cp controlsfx-8.0.0-developer-preview-1.jar:controlsfx-8.0.0-developer-preview-1-samples.jar org.controlsfx.HelloControlsFX

If you think you have a feature **you can contribute**, a bug you want to fix, or have a bug youd like to file, please direct it to the [issue tracker over at the ControlsFX bitbucket website][12].

If you **want to use** ControlsFX, then youre probably wondering how to use the API that weve slaved over for hours! In your case, the best and definitive location for help is definitely [our javadocs][13]. Fair not, these are not a barren wasteland of undescribed functionality weve poured our hearts into making these javadocs full to the brim of examples, commentary and explanation. If anything is unclear to you, [file a bug in our issue tracker][12] and well do our best to update the documentation straight away!

Another great place to explore is our **sample code**, all located in the [src/samples directory][14] of our [code repository][15]. Weve put a bunch of effort into making these examples something you can learn from.

### Release Versioning

ControlsFX has a slightly different approach to version numbers than other projects. We use the fairly traditional x.y.z numbering system, except in the case of ControlsFX, the x.y portion is used to represent the base JavaFX version required. In other words, ControlsFX 8.0.0 is the first release of ControlsFX to work on JavaFX 8.0 and above. ControlsFX 8.1.5 (if we ever release that version) is used to represent that the release will work on JavaFX 8.1 (and not JavaFX 8.0), and is the 6th release (remember: real programmers count from zero ![:-\)][16] ).

In other words, we do not differentiate between bug fix and feature releases we will clarify what the release contains on a per-release basis. Also, we will always aim to require the minimal version of JavaFX possible, but we are also not going to hold back features / bug fixes / etc if we can resolve them by moving to a newer release. Prior to moving up to a new JavaFX version we will always tag the [repository][17] and make available a download of the source and compiled code for the earlier version, for people who are unable to move to the newer JavaFX release.

### License

ControlsFX is licensed under the [3-Clause BSD license][18]. We are not lawyers, but our interpretation of this license suggests to us that it is business friendly, requiring only the redistribution of the [3-clause BSD license we distribute with ControlsFX][19]. As always, I suggest you review the license with the appropriate people, rather than take the advice of software engineers. If this license is not suitable, please contact [Jonathan Giles][20] to discuss an alternative license.


   [1]: https://bitbucket.org/JonathanGiles/controlsfx
   [2]: http://cache.fxexperience.com/wp-content/uploads/2013/04/buttonBar.png
   [3]: http://cache.fxexperience.com/wp-content/uploads/2013/04/dialogs.png
   [4]: http://cache.fxexperience.com/wp-content/uploads/2013/04/gridView.png
   [5]: http://cache.fxexperience.com/wp-content/uploads/2013/04/rangeSlider.png
   [6]: http://cache.fxexperience.com/wp-content/uploads/2013/04/rating.png
   [7]: http://cache.fxexperience.com/wp-content/uploads/2013/04/segmentedButton.png
   [8]: http://jdk8.java.net/download.html
   [9]: http://fxexperience.com/downloads/controlsfx-8.0.0-developer-preview-1.zip
   [10]: https://bitbucket.org/JonathanGiles/controlsfx/src/ba2f89a26ff4b87ae04f80135c47d204d82efdee/src/samples/java/org/controlsfx/HelloControlsFX.java?at=default
   [11]: https://bitbucket.org/JonathanGiles/controlsfx/src/ba2f89a26ff4/src/samples/java?at=default
   [12]: https://bitbucket.org/JonathanGiles/controlsfx/issues
   [13]: http://www.jonathangiles.net/javafx/controlsfx/javadoc/
   [14]: https://bitbucket.org/JonathanGiles/controlsfx/src/ba2f89a26ff4b87ae04f80135c47d204d82efdee/src/samples/java/org/controlsfx?at=default
   [15]: https://bitbucket.org/JonathanGiles/controlsfx/src/ba2f89a26ff4?at=default
   [16]: http://cache.fxexperience.com/wp-includes/images/smilies/icon_smile.gif
   [17]: https://bitbucket.org/JonathanGiles/controlsfx (Announcing Scenic View 8.0.0 Developer Preview 3)
   [18]: http://opensource.org/licenses/BSD-3-Clause
   [19]: https://bitbucket.org/JonathanGiles/controlsfx/src/e01d9073145a352db1562baf6ea7297d5c37d6a1/license.txt?at=default
   [20]: mailto:jonathan%40jonathangiles.net