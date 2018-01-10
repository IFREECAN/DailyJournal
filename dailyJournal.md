




****************************************************************************************************************************
Date: Sunday 12.24.14

While preparing to 301 entrance test I read the chapter called "THE ABC OF PROGRAMMING" from our textbook.
Even though I know the main functions of HTML, CSS and JavaScript on a website, re-reading this chapter helped reinforced and clarify some information.

****************************************************************************************************************************
(weekIII) Date: Friday 12.22.17

Today we did an overview of course 201 and what to expect in 301 and 401.
Brian provided more detial on what to expect in 301.

The main goal of a function is to encapsulate codes… so we can call it when we need it later.

Brian encouraged us to keep writing loops untit the syntex become common muscle memory activity.
 > learn/review "for each"

****************************************************************************************************************************
(weekIII) Date: Thursday 12.21.17

Review of next course "Course 301" -- by Brian
propal syntex of object lateral:
    var car = {
make: 'toyota', // data-type = 'string', mike = property, 'yotota' = value of the property.
model: 'camry', // data-type = 'string', model = property, 'camry' = value of the property.
year: 2015, // data-type: intiger; year = property, 2015 = value of the property  
};

Today I went over some of our topics to learned more about the different parts of functions, objects to get getter understanding of what each part means and what they do...

****************************************************************************************************************************
(week III) Date: Wednesday 12.20.2017 ---
Today I learned about creating a learning mindset and being open to the learning process, even when it is difficult. And this is especially true in the technical industry (on the job) where tools and practices are changing at a fast rate. Being able to commit to learning and applying myself… “If you stick to it and complete 401 you will be able to perform, and develop the mindset to learn things you don’t already know….”
Topic: Persistence layer – how long will/can your data persistence?
	Non-secured persistence layers… example is cookies.
Local storage API
	> it is completely bound to your local machine only
	> local storage is tired to browser and domains it does not function between different browsers.  
	> local storage object –
How do we work with local storage?

localStorage.setitem (‘user’, ‘brian’) – user | use this formite instead: localStorage.user = ‘brain’;
localStorage.getitem (‘user’) – getter |  use this format instead: localStorage.user; note:: and this will get you brains.
How to delete a property on an Object:
	delete localStorage.user;
	> All local storage data must be house as Boolean, string or integer. … You cannot save an object, as an object, to a local storage.
Key-point:***When see “[object Object]’’ this means you are trying an object as a regular object and you can’t do that to localStorage… to solve this you will JSON.stringify the object to add it as a string, and JSON.parse the stringed object to make it an object again.
New info: JSON –
To get an object in a local storage you stringified the object by json
	Json stringify the object to get it in the local storage and jsan “parse” the object to get it out
	Example: (to get it in)  localStorage. Course = JSON.stringify **
		(to get it out) JSON.parse(localStorage.course);
NOTE::: add ordering of a list is not retain (when retrieved it will show up in any order) , ordering of an array is retained.
How to remove local storage:
Session-storage – a sessionStorate is similar to Window.localStorage; the difference is while data stored in localStorage has no expiration set, data stored in sessionStorage gets cleared when the page session ends. // MDN.

****************************************************************************************************************************
(weekIII) Tuesday: December 19, 2017
Today I learned and created user stories about multiple group of interest for the same product. I wrote a user story for a marketing research time, the end-users and the development team.
I also learned about JavaScript plugins that can used on canvas element to create amazing images HTML5 pages.
What is a canvas element?
 it is an HTML element which can be used to draw graphics using scripting (usually JavaScript)
> it can be used for drawing, making animations and photo composition.
> <canvas> is similar to the <img> element but one difference is that <canvas> element have closing </canvas> tags.

****************************************************************************************************************************
(weekIII) Monday:  December 18, 2017

Today we learned about media tags using JavaScript and HTML. We learned about start and pause tags that allows us to play/pause music and videos.
Sample code from class: github.com link: https://github.com/codefellows/seattle-201d29/blob/master/11-audio_video_tracker/lecture/app.js
Usestrict';

	var video = document.getElementById('lecture-audio');
	var start = document.getElementById('audio-start');
	var pause = document.getElementById('audio-pause');

	function handleAudioStart() {
	  video.play();
	}

	function handleAudioPause() {
	  video.pause();
	}

	start.addEventListener('click', handleAudioStart);
	pause.addEventListener('click', handleAudioPause);

****************************************************************************************************************************
(weekII) Friday: December 15, 2017

What is an ojbect lateral:
a literal is a notation for representing a fixed value in source code. Almost all programming languages have notations for atomic values such as integers, floating-point numbers, and strings, and usually for booleans and characters; some also have notations for elements of enumerated types and compound values such as arrays, records, and objects. An anonymous function is a literal for the function type // wikipedia
Ecample from class:
Var object = {
	Prop1: ‘var’  …this is a string
	Prop2: true, … this is a boolean
    Prop3: 1, .....this is an integer

We also review this weeks project and topics.


****************************************************************************************************************************
(weekII) Thursday: December 14, 2017
    CSS layout (pages: 358-403)

Web browsers will display images in normal flow unless developers specify the relative, absolute or fixed position(s) of contents. CSS Frameworks provide rules for common tasks.
CSS treats HTML elements as indivicual boxed items and the boxed element are either block-level or inline-level.
Example of inline-level elements are <img>, <b> </b> and <i></i>; while some examples of block-level elements are <h1></h1>, <p></p> and <ul> <li></li></ul>.
Position schemes for SCC are normal flow, relative positioning, and absolute positioning. Each of these schemes allows developers to control the layout of a webpage.

****************************************************************************************************************************
(weekII) Wednesday: December 13, 2017
    Here is what read about in the textbook:
    To create an empty object usin literal notation use:
	var some object = {}
the curly brackets create an empty object.

Example of object using literal notation:

	var hotel = {
	  name: ‘Quary’,
	  rooms: 40,
	  booked: 25,
	  checkAvailability; function() {
		return this.rooms – this.booked;
  }
};

var elName = document.getElementById(‘hotelName’);
elName.textContent = hotel.name;

var elRooms = document.getElementById(‘rooms’);
elRooms.textContent = hotel.checkAvailability();

NOTE.: the result is 15 rooms. (textbook pare 104)


****************************************************************************************************************************
(weekII) Tuesday: December 12, 2017

OOP = object oriented Programming

Note:
OOP = object oriented Programming

Each store location is it own “object” {}

Objects are:
Characteristic + behaviors,
Information + Actions,
Nouns + Verbs,
Properties + Methods

Properties of the objects:				methods
	Min Customer each hour = [ ] 		calc
	Max	cookies each hour = [ ]		    calc
	Avg name					        render( )

Note:
Constructor Functions starts with a capital letter.
The job of a constructor function is to create objects (called instances)

InnerHTML vs. 		TextContent
	<div> 			<div>Woo!</div>
	<p>Woo!</p>
	</div>

****************************************************************************************************************************
(weekII) Monday: December 11, 2017

Intro to Markdown – Used for documentations of your work
What is a Markdown: a lightweight markup language with plain text formatting syntax. It is designed so that it can be converted to HTML and many other formats using a tool by the same name.[8] Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor. // Wikipedia
Example: Markdown: https://dillinger.io/

Intro to Js Objects --
Intro to the DOM – Document Object Model, it is the programming interphase  for HTML documents.
//Assignment Prep

Example of an object.
Var obj = {
	(property) -String: “some string, ( “some string” is the value of the property String, and it’s data-type is called a string)
	(property) -Num: 15, (15 is the value of property Num and it’s data-type is a integer)
	(property) Items: [ house, cat, 5],
	(property) toggle: true, ( “true” is the value of the property toggle, and it’s data-type is called a Boolean)
}

****************************************************************************************************************************
(WEEK I)
