# Hoth or Not
## Timour, Mike, Chris and Adam

* Note- ask jared to break down get/post requests
* ask him why they are both named post
        

### Thursday 3/8/18
* work on using client side logic to make SWAPI call-> AJAX can be used if neccessary
* work on loading results page
* further styling
* DEPLOY TO HEROKU

### Wednesday 3/7/18
* finish results page and integrate generate score function
* connect html pages to each other
* work on getting the jss to target correct html
* additional animations and styling
* figure out ideal way to generate images for each character
    * several options, some better than others


### Tuesday 3/6/18 Notes
* redesign html according to new wireframe
* continue working on firebase to allow it to alter the correct data
* work on rotating through the array of characters
* begin implementing data attribute for api calls
* look into using a second api (twitter?)

### Monday 3/5/18 Notes
* Mike will be learning firebase to allow handling of the data
* Chris will be exploring second APIs 
    * He will also be learning motionsoft
* Timour is handling the frontend and deciding on a CSS framework
* Adam is working on serving the page and doing user flow/wireframe

### List of needed functionality
* homepage
    * when clicking any of the ranking columns, display the according rankings
* when clicking either of the images, log the user vote and display a new pair of images
* when clicking the 'learn more' button, link to a new page that has information about that character pulled from star wars API
* when clicking the 'bonus' button, link to a new page that will have functionality TBD


#### Documentation and planning
* Wire frames
    * landing page - https://wireframe.cc/DyhXAv
    * game page -https://wireframe.cc/W9Lo8Q
    * score page -https://wireframe.cc/SKWBo0
* User flow - https://drive.google.com/file/d/1jnPZsDNGfWmSPxwPoextMTTHXIzL9xXd/view?usp=sharing
* Initial character list - https://docs.google.com/document/d/1JoyL6zobM8YuT4f8jhmLleU0bw1rsTvaWGYiEP9_cg4/edit
* Character Image list - https://docs.google.com/document/d/1QuTDyrtCUFeVtRuAtCCCPYpzAVZRVi7P6R12SBxx9zc/edit?usp=sharing

#### Technology links
* Star Wars API documentation - https://swapi.co/documentation
* GIPHY API node package - https://www.npmjs.com/package/giphy-api
* SWAPI node package https://www.npmjs.com/package/swapi-node
    * will be using http://swapi.co/api/people/?search= endpoint to search for charcaters
    * result.results[0]."insert desired parameter here"
* Motion UI - https://zurb.com/playground/motion-ui
* Matererliaze CSS - http://materializecss.com/getting-started.html
* Firebase - https://firebase.google.com/
    * Database - https://console.firebase.google.com/project/hoth-or-not-d14ab/database/hoth-or-not-d14ab/data