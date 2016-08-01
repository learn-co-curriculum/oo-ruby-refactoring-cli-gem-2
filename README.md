
#Refactoring a CLI Gem (Concert Gem)
​*This video walks through an extended extended process of refactoring a CLI Gem*​

*A session between a Student and Avi Walking through their CLI Gem and refactoring extensively

## Objectives

1. Distinguish between Classes and their Instances
2. Create powerful and dynamic Scraping methods
3. Test and debug in console
4. Explain the advantages and disadvantages of the zipper pattern to combine arrays to create objects
5. Use user Input to display a specific Object


## Video

<iframe width="100%" height="720" src="https://www.youtube.com/embed/Lt0oyHiKWIw?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>


## Summary

* Objects 
 * Class variables and properties vs instance properties
 * Object orientation vs functional programming
* Fix the Scraper methods
* The Zipper pattern
* The 'Or equals' memoization 
* Test in the console
 * Pry and other debugging methods
 * Build reload! method to reload code changes into console
* Scrape and capture properties using the zipper pattern
 * Create objects with those properties
* Utilize these changes in our CLI Class
 * Scrape and persist data to objects when the app starts up
* Iterate and display our Concert Objects
 * Fix the menu method
* Use user input to grab appropriate Object
 * Use the `Concerts.all` method to determine how many concerts we have
 * `Array#count` method
 * `Integer#between?` method
 * Check the docs for available methods for arrays 
* Find Concert with the `Concert.find` method
* Use returned Concert object to return it's attributes
* Debug and fix the 'No method' error   
* Tips on building another application using these ideas
* Tips on avoiding the Zipper pattern
* Talk about the power of Object Orientation
 * Think about the objects in physical space
 * Think about method returns
* Figure out average length of artist names in our data
 * Use iteration over Concert Objects
 * Talk about `Array#collect` method
* Tips on internalizing the concepts
 * Solidify concepts - move slowly!


## Code

[Original Code](https://github.com/benser1/cli-upcoming-concerts/tree/8652e5c285ca779fd2fa94f0490f726a0ec22b6f)

[Refactored Code](https://github.com/benser1/cli-upcoming-concerts)
<p class='util--hide'>View <a href='https://learn.co/lessons/oo-ruby-refactoring-cli-gem-2'>OO Ruby Refactoring CLI Gem 2</a> on Learn.co and start learning to code for free.</p>
