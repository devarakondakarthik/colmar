# Colmar Academy

The capstone project for *CodeCademy Ready*.

## Description
>You are tasked with designing and creating the landing page for a new school. You will help them by making informed design decisions about color and typography using the skills you learned last week. You will then implement your design[...] For this project you will implement the site specified by the wireframes and make all remaining design decisions to complete the site.

## Design notes
- CSS animations indicate which portions of the website are clickable
- Animations echo the blue/yellow color theme
- Layout implemented in rem instead of px
- Added several layouts between desktop and mobile to ensure that a wide variety of devices can access site
- Uses semantic tags and alt text where appropriate
- **Experimental layout and style in progress on branch new-design**

### Color palette
I let the images of this site drive the color palette. Four "types" of colors seem to predominate: web-y blues, yellow ochres, warm greys, and warm browns.  I focused on the first three families.  I went with a dark, high-impact navy blue for header, footer, and important features like buttons, with a poppier blue for hover actions.  I used a mustard/ochre for select features like logo and main header. I kept the backgrounds simple with alternating grey and light tones.

In order to accommodate the dark blue header, I edited the SVG logos to fill white instead of black.

I intended the colors to be impactful (but not distracting) and just the slightest bit informal.

### Fonts
Given the technical, urban brand of Colmar Academy, I chose to use a sans serif font.  I chose "Web safe" fonts to maximize the chances viewers will see the correct font in the correct layout.  Arial was my ultimate choice for non-header text; it's clean and readable.  I used Arial Black for the headers to increase their impact.

I considered using Courier for the headers -- it added visual interest to the page and would have been a cheeky nod to the tech content of most of the courses -- but ultimately found it decreased the readability of headers with lighter colors.

### Changes
- **Omitted 185px space at top of mobile layout.** I made a deliberate choice to exclude this page element because I felt it detracted from the flow of the site.
- **Used ratios instead of widths in most cases.** CSS seems to behave better with the `flex` property than with widths. In some instances this required ignoring what the specs said - for instance, the "information" links were supposed to be 423px wide.  I made them resize responsively instead, so that the large image to their left would maintain its size in relation to the image above it.

## Experimental Design
There's a limit to what you can do, style-wise, when you're limited to the layout specified in the wireframes.  I branched this repo to play around with alternate styles and layouts. The one currently under development fits the content to the viewport (no scrolling) and displays the different sections using a navbar on the side ... all in CSS! It's not pretty yet, but it's fun.
