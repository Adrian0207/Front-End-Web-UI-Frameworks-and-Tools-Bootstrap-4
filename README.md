# Front-End Web UI Framework and Tools: Boostrap4
### Week 1:
-*Setting up Your Development Environment: Git and Node*

    ♦Set up a Git repository and perform basic Git operations
    
    ♦Set up and use online Git repositories

    ♦Use Node-based modules to perform basic operations.

    ♦*Setting up Git*

        ♣Install Git on your computer

        ♣Ensure that Git can be used from the command-line or command-prompt on your computer

        ♣Set up some of the basic global configuration for Git

    ♦*Setting up Node.js and NPM*

        ♣Complete the set up of Node.js and NPM on your machine

        ♣Verify that the installation was successful and your machine is ready for using Node.js and NPM.

-*Introduction to Bootstrap*

    ♦Identify the purpose of using front-end UI frameworks in web design and development
    
    ♦Set up a project with Bootstrap support
    
    ♦Configure a web project to use Bootstrap
    
    ♦Become familiar with the basic features of Bootstrap

-*Responsive Design and Bootstrap Grid System*

    ♦Understand the reasons for using responsive web design in a web project

    ♦Use the Bootstrap grid system to design responsive websites
    
    ♦Add your own custom CSS classes to a Bootstrap based web project

-**Note for future me:**
    
    ♥To recreate the node_modules folder by typing **npm install** at the prompt.

    ♥To recreate the bootstrap folder run **npm install** firts and then install bootstrap with 
    **npi install bootstrap**.

    ♥Use **npn start** to run the index.html.

    ♥To see the aboutus.html write in the search bar http://localhost:3000/aboutus.html.
### Week 2:
-*Navigation and Navigation Bar*

    ♦Understand the need for navigation support in a web project

    ♦Use the Bootstrap navigation features including the Navbar and breadcrumbs in providing 
    navigation support in websites

    ♦Use icon fonts for decorating your website with meaningful graphical elements
-*User Input: Buttons and Forms*
    ♥Create and style buttons on a web page using Bootstrap button classes

    ♥Create and style forms on a web page using Bootstrap form classes

-*Displaying Content: Tables and Cards*
    ♦Present and style tabular data in a table form using Bootstrap support for tables

    ♦Display content using a card on a web page.
-*Images and Media*

    ♦Use images and media and include them in your website

    ♦Support responsive images and media using responsive Bootstrap classes for images and media

    ♦Use thumbnails and media components using Bootstrap classes

-*Alerting Users*

    ♦Include labels and badges in your web page
    
    ♦Create, style and include alerts in your web page
    
    ♦Appreciate the use of progress bars and controlling the state of the progress bars.

-**Note for future me:**

    ♥For using icons use npm by typing the following at the prompt:

        ♣**npm install font-awesome@4.7.0 --save** 
        ♣**npm install bootstrap-social@5.1.1 --save**

### Week 3:
-*Bootstrap JavaScript Components*

    ♦Understand the various Bootstrap components that require JavaScript support in order to function

    ♦Use the data-* attributes that Bootstrap's JS API provides for you to control the JS components 
    without writing a single line of JS code

-*Tabs and Tabbed Navigation*
    
    ♦Design a tabbed navigation for your content
    
    ♦Use tab panes to organize the content and navigate the content using tabbed navigation

-*Hide and Seek*

    ♦Use the collapse plugin to hide/reveal content

    ♦Construct the accordion using cards

-*Revealing Content*

    ♦Set up a tooltip to be displayed when the user hovers over an area of the page
    
    ♦Enable popovers when the user clicks on a link or button
    
    ♦Reveal and hide modals when the user clicks on a link or button

-*Carousel*

    ♦Use a carousel component in your web page

    ♦Configure various aspects of the carousel

    ♦Add controls to the carousel to manually control it

### Week 4:
-*Bootstrap and JQuery*

    ♦Understand how to use JQuery and JavaScript and Bootstrap's JS component methods to control the 
    behavior of the components.

    ♦Write JavaScript code taking advantage of the Bootstrap's JS component methods and JQuery methods 
    for controlling Bootstrap JS components

-*CSS Preprocessors*

    ♦Write Less and Sass code to define your CSS classes
    
    ♦Compile the Less and Sass code into the corresponding CSS classes

    ♦Note Less: 

        ♠Install the node module to support the compilation of the Less file **npm install -g less@**    

        ♠Next type the following at the command prompt to compile the Less file into a 
        CSS file **lessc styles.less styles.css**

    Note Scss:

        ♠Stall the node module to support the compilation of the Scss file to a CSS file. To do this, 
        type the following at the command prompt: **npm install --save-dev node-sass**

        ♠This will install the node-sass NPM module into your project and also add it as a 
        development dependency in your package.json file.

        ♠Next open your package.json file and add the following line into the scripts object there. This adds 
        a script to enable the compilation of the Scss file into a CSS file: **"scss": "node-sass -o css/ css/"**

        !!!If a old version of a styles.css is in the folder, first removed it and then type the above
        ♠In order to transform the Scss file to a CSS file, type the following at the prompt: npm run scss
-Building and Deployment
    ♦Configure NPM scripts and automate your web development
    
    ♦Prepare your project for being hosted on a web server

-**Note for future me:**
    ♥First, we install two NPM packages onchange and parallelshell 

    ♥Then, add the following two script items to package.json if you are doing the 
    exercise on a MacOS computer or a Linux computer:

        ♣**"watch:scss": "onchange 'css/*.scss' -- npm run scss",
        "watch:all": "parallelshell 'npm run watch:scss' 'npm run lite'"**
        
        ♣ on a Windows computer, please use the following two script items instead of the above:
         **"watch:scss": "onchange \"css/*.scss\" -- npm run scss",
         "watch:all": "parallelshell \"npm run watch:scss\" \"npm run lite\""**
    
    ♥You will also update the start script as follows:

        ♣"start": "npm run watch:all",

    ♥Then, type the following at the prompt to start watching for changes to the SCSS file, compile it to CSS, 
    and run the server: **npm start**

    !!!Install ** parallelshell@3.0.1**, not parallelshell@3.0.2

         



         
