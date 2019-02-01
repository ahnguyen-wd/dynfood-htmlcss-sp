# dynfood-htmlcss-sp
## **Single page website design of a food website**

Only using HTML5 and CSS3, I will develop a functional single page website displaying food related items (recipe, my favorite food, etc)

This is the first of my projects which will develop my portfolio. Let's see how far I can advance!

**Steps completed on this first project:**

__1. Created the hierarchy folder tree__
a. assets folder for files I will create
b. vendors folder for files others created

__2. To make css more consistent among all browsers, I normalized it by downloading a css file__
a. source: https://necolas.github.io/normalize.css/
b. <link rel="stylesheet" type="text/css" href="vendors/css/normalize.css">

__3. Setup the font that I will be using and link it in the head__
a. https://fonts.google.com/
b. Font Name: Lato
c. Experimenting with: Oswald (3 weights {300,500,700})
d. <link href="https://fonts.googleapis.com/css?family=Lato|Oswald:300,500,700" rel="stylesheet"> 

__4. Responsiveness Setup - Using Grids system__
a. We will be using http://www.responsivegridsystem.com/ today
a1. This is not a framework, rather a tool to create grids easily
b. Similar to bootstrap, but easier to maintain the code

__5. Content__
a. This stage will be where we start from the top down with content
b. Header -> Body -> Footer

**Study Notes**

__To remove all margin and padding, enter the following into the style.css:__
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

__To have maximum optimization with the text, it is best to set text-rendering to optimizeLegibility. This will adjust font-weight accordingly:__

In style CSS:
**text-rendering: optimizeLegibility;**