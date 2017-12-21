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



