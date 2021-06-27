# Understanding The Problem Domain and then make it codes
***lets agree first it Is The Hardest Part Of Programming***

<b>What is the hardest thing about writing code?</b>

- Learning a new technology

- Naming things

- Testing your code

- Debugging

- Fixing bugs

- Making software maintainable

<b>The list goes on and on.</b>

### Why problem domains are hard

The reason why puzzles like this one are so hard, is because you can’t really see what you are trying to build very clearly.  Normally when you put together a jigsaw puzzle you follow steps that might look something like this:

<ol>
<li>Figure out what the major components of the picture are</li>
<li>Sort the pieces by color or component</li>
<li>Put together all the border pieces</li>
<li>Put together each component of the picture from the piles you created</li>
</ol>

<b>This all breaks down when you don’t have a picture with clear components that you can identify.

The same thing happens when writing code.  Writing code is a lot like putting together a jigsaw puzzle.  We put together code with the purpose of building components that we have taken out of the “bigger picture” of the problem domain.

The big issue is that many problem domains are like a puzzle with a blurry picture or no picture at all.</b>

<b>The real world is a messy place.  Many of the problem domains we face as programmers are difficult to understand and look completely different depending on your viewpoint.

As programmers, we also are often not given complete information about the problem domain, so we don’t even have the information we need to understand it.
</b>

### Programming is easy if you understand the problem domain

A long time ago, I worked for Hewlett Packard writing software for multi-function printers.
Most of the work at the time was basic waterfall development.  There wasn’t much Agile happening there—at least at the time I was there.There was however something really interesting about the waterfall approach and the extreme amount of specification that was done before anything was built—it was very easy to write the code for a feature.

I remember writing a tab control for the user interface of a printer and having the complete pixel perfect specs handed to me before I began to write any code.  I was also given all the possible use cases and told exactly how it should function and what it should do under just about every circumstance.

Guess how easy it was to write the code to produce this tab control?  Super easy.

As much as I frown upon this approach for software development today, there is something interesting to think about here.

I was essentially given the entire problem domain in the form of a spec that was clear and unambiguous
**I was easily able to learn that problem domain and because of it, I was able to write the code very easily as well.** 
Perhaps you have had a similar experience, not necessarily working on a waterfall project where you were given the spec, but perhaps on an Agile project where you took the time to clearly understand the problem domain before writing any code.

I’ve spent days trying to implement a feature only to finally go back and talk to a product owner and hash out completely how something should work and why it should work in a particular way, only to go back to my desk and crank out the code in a matter of hours.
<b>What can you do about it?</b>
If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:
<ol><li>Make the problem domain easier</li><li>Get better at understanding the problem domain</li></ol>

# objects

<b>Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names. </b>


<b>IN AN OBJECT: VARIABLES BECOME                                                                              
KNOWN AS PROPERTIES                                                
If a variable is part of an object, it is called a            
property. Properties tell us about the object, such as            
the name of a hotel or the number of rooms it has.                 
Each individual hotel might have a different name                     
and a different number of rooms.</b> 

<b>IN AN OBJECT: FUNCTIONS BECOME 
KNOWN AS METHODS 
If a function is part of an object, it is called a method. 
Methods represent tasks that are associated with 
the object. For example, you can check how many 
rooms are available by subtracting the number of 
booked rooms from the total number of rooms. </b> 

***THE DOM TREE IS A MODEL OF A WEB PAGE***

<p><img src="https://pbs.twimg.com/media/E2th_bxUcAEibUz.jpg:large" ></p>


<b>WORKING WITH THE DOM TREE</b>
<ol><li>STEP 1: ACCESS THE ELEMENTS</li><p>The terms elements and element nodes are used interchangeably 
but when people say the DOM is working with an element, it is actually working with a node that represents that element. </p><li>STEP 2: WORK W ITH THOSE ELEMENTS</li><p>DOM queries may return one element, or they may return a Nodelist, 
which is a collection of nodes. </p></ol>

