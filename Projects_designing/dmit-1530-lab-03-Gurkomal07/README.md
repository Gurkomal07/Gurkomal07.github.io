# dmit1530-lab-03

## Lab 03: Toggle Navigation With Drop-Down Menu

**Due**: Sunday @ 23:55 MST

**Weight**: 5% of your final grade

---

## Instructions

Clone a copy of this repository to your device so that you can develop it locally. When you finish, make sure to push your latest commit to GitHub Classroom. 

For this Lab, you will create a website with several pages and a fully functional top-level navigation. In the smallest (mobile) view, the user should be able to show and hide (toggle) the navigation with the click of a button. In the largest (desktop) view, the user should be able to hover or tab over a dropdown menu. 

This Lab will be  a Code-A-Long where you are expected to put in the final touches.

---

## The Build Methodology

Start by writing all of your HTML for ``index.html``. Remember to fill out all of your ``<meta>`` element information.

Next, you will need a ``<header>``, followed by a ``<main>``. 

Inside of your ``<header>``, you'll need a first-level heading, your monkey logo, and a ``<nav>`` with three drop-down menus. These menus should be structured as follows: 

	> Products

	>> Featured

	>> Popgrips

	>> Accessories

	> Customize

	>> Create For You

	>> Create For Business

	> Sale

	>> See All 

Because of the different states and layouts of your navigation menu, you will need a number of wrappers and helper classes (ex. .inner-container, .wide-flex, and .flex-container).

The skeleton of your code should look something like this:

```HTML
	    <header>
        <div class="inner-container wide-flex">
            <div class="flex-container">
                <!-- First-Level Heading Here -->
                <div class="menu-icon">
                    <!-- Monkey Icon Here -->
                </div> <!-- end of .menu-icon -->
            </div> <!-- end of .flex-container -->
            <nav>
                <ul class="main-menu">
                    <!-- Products, Customize, and Sale Menus Here -->
                </ul>
            </nav> 
        </div> <!-- end of .inner-container -->
    </header>
    <main>
        <!-- Main Content Here -->
    </main>
```

### CSS

With your instructor, work through your CSS. 

Begin with universal styles and helper classes, your mobile view, any classes necessary for your toggle menu and JavaScript, and finally your media queries. 


## JS

Be mindful of your CSS and the class names that you gave to specific elements when using the toggle script that we learned during our hamburger menu demo. 


### On Your Own

On your own, you will need to complete all of the other pages provided for you. Your goal is to have a fully functional site-wide navigation where the user can jump to any page from anywhere on the website. 

You will be responsible for:

1. Copying, pasting, and altering the HTML for each page (ex. adding a class to the &lt;body&gt;).

2. Writing a unique heading for each page.

3. Creating a unique background for each page by altering the gradient colours. 

>> **Note**: For colour ideas, try any of the following websites.

>> https://materialuicolors.co/

>> https://mycolor.space/?hex=%23882C63&sub=1

>> https://color.adobe.com/explore

>> https://coolors.co/55dde0-33658a-2f4858-f6ae2d-f26419

>> https://www.design-seeds.com/
