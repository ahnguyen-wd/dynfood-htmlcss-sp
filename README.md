# dynfood-htmlcss-sp
Single page website design of a food website

Only using HTML5 and CSS3, I will develop a functional single page website displaying food related items (recipe, my favorite food, etc)

This is the first of my projects which will develop my portfolio. Let's see how far I can advance!

Steps completed on this first project:

1. Created the hierarchy folder tree
a. assets folder for files I will create
b. vendors folder for files others created

2. To make css more consistent among all browsers, I normalized it by downloading a css file
a. source: https://necolas.github.io/normalize.css/
b. <link rel="stylesheet" type="text/css" href="vendors/css/normalize.css">

3. Setup the font that I will be using and link it in the head
a. https://fonts.google.com/
b. Font Name: Lato
c. Experimenting with: Oswald (3 weights {300,500,700})
d. <link href="https://fonts.googleapis.com/css?family=Lato|Oswald:300,500,700" rel="stylesheet"> 

4. Responsiveness - Using Grids system
a. We will be using http://www.responsivegridsystem.com/ today
a1. This is not a framework, rather a tool to create grids easily
b. Similar to bootstrap, but easier to maintain the code

Study Notes

To remove all margin and padding, enter the following into the style.css:
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

To have maximum optimization with the text, it is best to set text-rendering to optimizeLegibility. This will adjust font-weight accordingly:

In style CSS:
text-rendering: optimizeLegibility;