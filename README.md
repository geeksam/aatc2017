Smaller! Exercises
==================

This is the companion code to my Agile Alliance Tech Conference 2017 talk.
Slides for the talk can be found at http://boochtek.com/aatc2017.

Pair (or triple) up to work on the following exercises.

Don't forget to use your resources with more info on smells and refactorings:

* [Refactoring Catalog](https://refactoring.com/catalog/)
* [SourceMaking list of smells](https://sourcemaking.com/refactoring/smells)
* [Industrial Logic list of smells](http://www.industriallogic.com/wp-content/uploads/2005/09/smellstorefactorings.pdf)


Stories
-------

Start with these story-splitting exercises:

1. [Events](events.feature)
    * Overly detailed
    * Has `When` steps after `Then` steps
    * Checks more than 1 thing
2. [Electric Car](electric_car.feature)
    * Not customer-focused
    * Tries to do too much all at once
    * Asks for the impossible


Code
----

Choose from among the following exercises.
There's more here than you'll have time to finish during the workshop.
You might want to start out with a language that you're familiar with.
Or peruse them all and see which ones interest you.

1. [Installations Controller](installations_controller.rb) (Ruby)
    * Lots of duplicated code and nested conditionals
    * Extracted from some actual Rails code
2. [Roman Numerals](roman_numerals.java) (Java)
    * Overly complicated code, plus overly simplistic ("shameless green") code
    * From http://exercism.io/tracks/java/exercises/roman-numerals
3. [Roman Numerals](roman_numerals.cs) (C#)
    * Not a bad approach, but needs to be a bit more DRY
    * From http://exercism.io/tracks/csharp/exercises/roman-numerals
4. [Bowling](bowling.rb) (Ruby)
    * Inconsistent and cluttered formatting
        * It _looks_ like it has problems
    * Long methods
    * Probably at least 1 other class needing to be extracted
    * From http://exercism.io/tracks/ruby/exercises/bowling
5. [Bowling](bowling.js) (JavaScript)
    * One big function
    * From http://exercism.io/tracks/javascript/exercises/bowling
6. [Roulette](roulette.cpp) (C++)
    * Long functions
    * Needs to extract some classes for obvious abstractions
    * Lots of loops and conditionals
    * From http://thedailywtf.com/articles/the-end-of-the-lucky-deuce


More
----

For a more extensive refactoring exercise, I'd recommend the Gilded Rose Kata.
It's available in several variants in several languages.
Just google for `gilded rose kata` plus your programming language.

For even more refactoring exercises (in a more structured fashion),
I'd recommend [Refactoring Workbook](http://amzn.com/dp/0321109295) by William C. Wake.

You should also check out [Exercism](http://exercism.io/).
They've got a bunch of different exercises, and support several dozen different languages.
You write your code for a given exercise, and others give you feedback on how to improve it.
It's free to use; just sign in with your GitHub account.
You will need to install [a command-line program](http://exercism.io/clients/cli) to make submissions.
