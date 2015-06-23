BikeReady is evolving the way the world moves. By seamlessly connecting bikers to their bikes through our apps, we make cities more accessible, opening up more possibilities for bikers and more business for the community. BikeReady's rapidly expanding global presence continues to bring people and their cities closer.


##Demo##

https://bikeready.herokuapp.com/


##Initial Pseudocode /Outline Before Coding##

1. Initialize Rails app
2. Set up model structure
3. Seed DB with data from seed file 
4. Set up controller and initial view to display all necessary information for models (a subset of the models)
5. Stylize view
6. Create sorting feature
7. Ajaxify sorting (single page app)
8. Edge cases
9. Stylize view


##Technologies Used##

* Ruby on Rails
* HTML5/CSS3/Javascript
* jQuery
* handlebars.js Templating Framework
* Bootstrap CSS Framework


##Design Approach##

First, I started out with rails skeleton and implemented devise sign-up functionality. 

Then, I set up an initial controller and view with several "App" objects as samples. I started stylizing this page as well. 

Then, I set up the controller actions that will return Apps from different sorting methods. I put the methods in the "App" model since it seems like the model should be responsible for returning its own results.

After I got those methods and controller actions working, I started to incorporate Ajax on the front end to call those actions. This made the app entirely one-page and also gave me an MVP.

I started to create a header and nav bar on the sign-up page. 

Lastly, I went ahead and did some research on how to implement Google Maps API. What I needed my app to do with Google Maps API is to animate the marker on the map to simulate delivery. I researched and wrote the Javascript functionality to accomplish this. 

The rest of the time was dedicated to investigating on how to implement Twilio API for real-time messenging. 

Throughout the entire process, I worked on the front end and back end simultaneously. I also constantly went back and refactored many of my app's existing features while I was implementing new ones.


##Known Issues##

* Postmates API is not in sync with the bike delivery status update. 


##Desired Improvements##

* Refactor CSS for more consistency and improve media query breakpoints
* Learn and refactor Javascript into CoffeeScript


##Other Notes##

* How does the app keep updating its status to match with the Postmates API.
* Need to test on more browsers and devices
