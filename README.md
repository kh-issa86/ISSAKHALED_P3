# Project 3 of the OpenClassrooms web developer path: Boosting a website with CSS animations
***
### Skills assessed:
* Implement advanced graphical CSS effects
* Ensure the graphic consistency of a website
* Set up a navigation structure for a website

## Goals
1. Develop a site offering the menu of 4 major Parisian restaurants.
2. Allow online reservations and menu composition.

***
### Pages to integrate:
* Home pages
* Menu pages (4 in total)

#### Animations
##### Buttons
* On hover, the background color of the main buttons should lighten slightly. The drop shadow will also need to be more visible.
* Eventually, visitors will be able to save their favorite menus. For this, a heart-shaped "I like" button is present on the model. When clicked, it should gradually fill up. For this first version, the effect may appear on hover instead of on click.

##### Home page
* When the application has more menus, a "loading spinner" will be required. On this model, we want to have a preview. It should appear for 1 to 3 seconds when you get to the home page, cover the entire screen, and use CSS animations (no library). The design of this loader has not been defined, so any proposal is welcome as long as it is consistent with the site's graphic charter.

##### Menu pages
* On arrival on the page, the dishes should appear gradually with a slight time lag. They can either appear one by one, or by group “Starters”, “Main courses” and “Desserts”.
* The visitor can add the dishes he wants to his order by clicking on it. This brings up a small check mark to the right of the dish. This check mark should slide from right to left. For this first version, the effect may appear when hovering instead of clicking. If the title of the dish is too long, it will need to be cropped with ellipses.


## Technologies
***
* Allowed: HTML, CSS, CSS preprocessor (ex: Sass)
* Forbidden: JavaScript, inline CSS

### Graphic identity

Fonts:
* Logo and titles: Shrikhand
* Text: Roboto

Colors:
* Primary: # 9356DC
* Secondary: # FF79DA
* Tertiary: # 99E2D0

### Compatibility
On tablet and desktop, the site will have to adapt, but since these media are not a priority, their layout is free.
* The entire site must be responsive on mobile, tablet and desktop.
* Pages will need to pass W3C validation in HTML and CSS without errors.
* The site must be fully compatible with the latest desktop versions of
Chrome and Firefox.
