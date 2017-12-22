Date: Thursday 12.21.17

Review of next course "Course 301" -- by Brian
propal syntex of object lateral:
    var car = { 
make: 'toyota', // data-type = 'string', mike = property, 'yotota' = value of the property.
model: 'camry', // data-type = 'string', model = property, 'camry' = value of the property.
year: 2015, // data-type: intiger; year = property, 2015 = value of the property  
};

Today I went over some of our topics to learned more about the different parts of functions, objects to get getter understanding of what each part means and what they do...


Date: Wednesday 12.20.2017 --- 
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


Tuesday: December 19, 2017
Today I learned and created user stories about multiple group of interest for the same product. I wrote a user story for a marketing research time, the end-users and the development team. 
I also learned about JavaScript plugins that can used on canvas element to create amazing images HTML5 pages.
What is a canvas element? 
 it is an HTML element which can be used to draw graphics using scripting (usually JavaScript)
> it can be used for drawing, making animations and photo composition.
> <canvas> is similar to the <img> element but one difference is that <canvas> element have closing </canvas> tags.


Monday:  December 18, 2017

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

Friday: December 15, 2017 

What is an ojbect lateral:
a literal is a notation for representing a fixed value in source code. Almost all programming languages have notations for atomic values such as integers, floating-point numbers, and strings, and usually for booleans and characters; some also have notations for elements of enumerated types and compound values such as arrays, records, and objects. An anonymous function is a literal for the function type // wikipedia
Ecample from class: 
Var object = { 
	Prop1: ‘var’  …this is a string
	Prop2: true, … this is a boolean 
    Prop3: 1, .....this is an integer
    
We also review this weeks project and topics. 

