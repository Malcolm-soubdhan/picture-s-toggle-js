# pictures-toggle-javascript
js snippet to toggle between 2 pictures on click.

Js code is based on MDN's javascript tutorial and recommendations.

/*main steps: */

/*
1- we define a variable "myImage"; Then, we use a js method, "querySelector", 
on the DOM's object "document". 
With the method "querySelector", we select the first element "img"; 

2-Then, we put an event listener on the variable, with 2 arguments: 'click',
 and an anonymous function.

 3-this anonymous function define  another variable," mySrc",to which 
 we apply the method "getAttribute" to get the picture's src attribute.

 4-Then, we use a conditional structure to etablish that if we get a picture 's src, 
 we want to set the other's picture src instead, to toggle between the two pictures. 
 */
