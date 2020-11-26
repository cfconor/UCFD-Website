# *You For Coffee?* - A Dedication to Coffee 

## Introduction

*You For Coffee?* is inspired by the relatively recent but significant rise in coffee culture in Ireland. It is created to help educate visitors on some good methods to create a good cup of coffee, while providing resources to educate, and finally some links to some of the fantastic coffee roasters found around the country.

## Table of Contents

1. [UX](#ux) 
    - Project Goals
    - Customer Goals
    - Developer Goals
    - User Stories
    - Design Goals
    - Wireframes

2. [Features](#features)
    - Implemented
    - Planned

3. [Testing](#testing)
    - Images

4. [Deployment](#deployment)

5. [Credits](#credits)
    - Table of Contents Layout



## UX

### Project Goals

Create a website educating visitors about the beverage of coffee.

### Customer Goals

- To find out how to make a good cup of coffee using beans or ground beans.
- To learn some info about the coffee drink, its history and its culture.
- To figure out where customers could purchase local coffee from irish roasteries.

### Developer Goals

To create a well-structured informative website that provides some useful, practical information in a pleasant visual format, laid out into separate pages to avoid cognitive overload.

### User Stories
- I want a simple guide to make a cup of coffee, because I do not know how to best make coffee
- I want a navigation tool to easily get to each page, because I do not want to click several links to get the information I need
- I want a visually pleasing webpage, so that I do not get bored easily
- I want to learn more about where coffee originated from, because I am curious where the beverage comes from
- I want to know if there are any health benefits to drinking coffee, because I now often drink coffee
- I want to learn more about coffee culture in Ireland, because I am seeing more evidence of it in my locality
- I want to know where I can buy coffee, so that I can make a purchase
- I want to know if I can buy coffee in Ireland, so that I can make a purchase
- I want to know where in Ireland coffee can be bought, so that I can make a purchase
- I want to know if there is an easy way to make coffee, because I have a small budget and would still like to enjoy coffee
- I want to find all the different ways to make coffee, so that I can choose one.

### Design Goals

- Consistent header across all pages to encourage clear branding, and remind visitors that they are still on the same website.

### Wireframes



## Features

### Implemented

- Simple navbar that allows one-click navigation across all webpages, consistent design on all webpages to support first-time learning.

### Planned

- Step-by-step instructions with pictures on how to create 'the perfect cup of coffee'
- A simple summary document that gives the steps required to make The Perfect Cup. This would be a pdf one page doc that can be downloaded and printed out by a visitor, to stick on    a fridge or near the kettle.


- A page with separate sections for:
    - Coffee: a Brief History
    - Coffee Culture
    - The Health Benefits of Moderate Coffee Consumption

- A map of ireland with locations for a number of irish roasteries.

- A bootstrap carousel for the various other methods available for making coffee, with pictures, captions and links.

## Testing

### Images 
The images originally sourced as free stock images from pexels.com where very large (>4000px) jpg files, so the loading times were slowed considerably when initialliy loading the pages. Therefore, one of the first steps in importing this images for use was to downsize them to a smaller resolution, making the files smaller in size, with the aims of speeding up initial loading times. 

The initial log image was replaced with another, this time a soft-edged circular image in png format, which complimented the header better. I initially tried to make the min-height here 200px which matched the dimensions of the logo image, however had to push this out to 210px as it was cutting the bottom of the image and making it ugly.

Initialliy a picture (pouring-water.png) began causing loading time increases while running the website locally, so it was converted to .jpg and scaled down as small as possible while still keeping the clean layout.

### Instructions on Brewing Coffee
The original method I attempted for this was to use rows for each step in the instructions to ensure that they had their own space that could be easily manipulated for different viewports. Upon reviewing the bootstrap documentation however, it became clear that there was an alternative called [media object](https://getbootstrap.com/docs/4.0/layout/media-object/), which seemed more appropriate to the text-picture combo of content delivery I was looking for.

### Issue with header and footer not stretching over Full Width

On super-wide monitors, the header and footer seem to leave a gap at the edge of the screen. I will investigate this further once high priority objectives are complete

### Carousel implementation for equipment.html
This became problematic quickly, and was a fairly new concept to me, so after some tinkering I decided to lay this planned feature aside for a future release, as to study this component to the point of being able to implement it in a responsive setup would be difficult in the time remaining before project submission.

## Deployment

## Credits 

### Table of Contents Layout

The table of contents used in this readme was heavily inspired by the example given in the Code Institute videos for this module, as I felt they covered all the requirements for a solid readme design. 

### Navbar Layout

The layout of the header and navbar was heavily inspired by the resume project done in the User-Centric Design module, as it was a clean and feature-rich example of what can be achieved with bootstrap. 

### Colour Palette

The colour palette was heavily inspired by the great website [coolors.co](https://coolors.co/), which provided some great examples of colours that worked well together, to help find the theme that was suitable for the site.