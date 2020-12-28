---
title: Getting Griddy with it
date: "2018-03-10T16:44:37.121Z"
template: "post"
draft: false
slug: "getting-griddy-with-it"
category: "Technology"
tags:
  - "CSS Grid"
description: "7th March 2017. CSS Grid is released on Mozilla Firefox 52. The tech world is in awe of this new two-dimensional grid-based layout system. In this case however, it’s not strictly out with the old and in with the new."
socialImage: "/media/getting-griddy-with-it/image-5.png"
---

7th March 2017. CSS Grid is released on Mozilla Firefox 52. The tech world is in awe of this new two-dimensional grid-based layout system.

In this case however, it’s not strictly out with the old and in with the new.

The method of using grid templates is not new, with the concept being traced back to the 1930’s where it was seen as an international style, being rational and scientific. Over the past century, grid based layouts have been used in the printing industry with popular magazines such as NME following this format. In order to follow this, content was aligned within a series of rows and columns, allowing for consistency throughout said material. An example to see this in action is looking at print materials such as catalogues, where items follow a strict layout throughout its entirety. This method, whilst it can be considered boring in print, when you look through the entire Argos catalogue (a childhood pleasure), it worked in terms of design. It was simple for the user to read, design was consistent throughout and it flowed as well as could be hoped. From this alone, its surprising that the concept wasn’t brought into website design earlier.

![NME magazine grid layout](/media/getting-griddy-with-it/image-1.png)
*NME magazine grid layout*

In fact, concepts of grid are all around us without us even realising. Many icons and images derive from proportions and geometry, with Bing making use of this (Creative Bloq, 2015).

![Bing’s use of geometry and grids](/media/getting-griddy-with-it/image-2.png)
*Bing’s use of geometry and grids*

So on to grids on the web, does this mean all websites are going to look the same in terms of design and layout? 

This is the main concern I had before jumping into grid. I’ve found over the past few years that I’m limited by what I can do in terms of design when using methodologies such as Flex-box which left me following very standard, boring designs. There is only so much that you can do whilst floating elements and I hoped CSS Grid would be the difference so I went into my first “lesson” with my eyes open.

![Website Design Templates](/media/getting-griddy-with-it/image-3.jpg)
*Website Design Templates*

Reading up on Grid through websites such as CSS Grid Layout (W3Schools, No Date) and A Complete Guide to Grid (CSS-Tricks, 2018) made for a comfortable first-time experience with the process, walking me through step by step and exciting me for the prospect of what could be done.

I’ve had an idea for a portfolio for a number of months now but replicating this in Flexbox never matched the vision I had, resulting in portfolio pieces that I like the look of but don’t match what I really wanted to create. My previous portfolio which is shown below was the result of an adaptation I had to create due to the inability to show the design the way I wanted.

![Previous Portfolio Design](/media/getting-griddy-with-it/image-4.png)
*Previous Portfolio Design*

To be able to begin the process of my redesign in grid, I created a photoshop mock-up of my ideal design, where columns were created over the design to be able to create a basis for how the site would be coded.

![Photoshop Mockup Of Demo Portfolio](/media/getting-griddy-with-it/image-5.png)
*Photoshop Mockup Of Demo Portfolio*

During the process of coding the website, I did make changes to the design to what I felt worked better inside the grid design that I created. The change to add the blue corners on the page was done to show that the page was created in Grid. In my eyes, when you look at this, the grid gaps show the fact the page has been designed in CSS Grid, an important skill that I would want to show on my portfolio in the future

![CSS Grid version of Demo Portfolio](/media/getting-griddy-with-it/image-6.png)
*CSS Grid version of Demo Portfolio*

The concept of designing in Grid was simple; create an item and define what row and column you want it to be located in. A column set to be 5% of the viewport width was used to create a margin throughout the site. One of the issues that I had to be aware of was placement in each cell, as content is set to start in the top left, an issue easily sorted through margins on the item. The hardest task I faced was to ensure the site was responsive. This took a while, opting for a newly designed grid which would display on smaller devices i.e phones and tablets.
While desktops display a grid of 7 columns, mobile devices only show 4 therefore more of the content was stacked vertically, much the same as is done in Flexbox. Media queries were designed to reflect this change and also used to alter the size of the separating images so they got bigger as the display grew in size. The resulting demo site is that responsive, it can be displayed on Nintendo 3DS!

![Demo Portfolio on a Nintendo 3DS viewport](/media/getting-griddy-with-it/image-7.png)
*Demo Portfolio on a Nintendo 3DS viewport*

So, Grid is amazing?

Well no, but it has the potential. CSS Grid is still a very new concept and understandably isn’t complete or perfect (is anything ever?).

It is not currently supported by all browsers, with the main culprit being Internet Explorer. Although CSS Grid came to fruition from Microsoft, the methodology is not fully supported in IE. There are ways around this issue, as Rachel Andrew has documented (Andrew, 2016), using the “-ms” prefix on attributes such as grid columns. Whilst Internet Explorer does support several different attributes of Grid, others are completely missed out, for example grid gaps. This is due to Microsoft opting to support 2011 specifications as opposed to the far more advanced specifications that most browsers now support. 

![CanIUse showing CSS Grid Browser Support](/media/getting-griddy-with-it/image-8.png)
*CanIUse showing CSS Grid Browser Support*

With any new technology, bugs are always going to be an issue and CSS Grid is no exception. Created by Grid pioneer Rachel Andrew, grid users are able to submit any issues that they find to a specific GitHub repository. This overtime will be updated and be a valuable tool for users to be able to work around browser specific issues, before the browser support is universal. Thankfully I didn’t come across any issues during the development however this demo was designed to show the basics of CSS Grid in terms of display and how effective the mobile responsivity can be. Whilst being happy with the progress of the design that I’ve created, I’m looking forward to adapting this demo further, incorporating more skills and design features, to get the page up to a standard where it can be the forefront of my new personal portfolio.  

As I delve further and further into grid over the coming months, I can envision encountering issues that I haven’t found before due to these bugs but as Grid becomes more commonly used and the browser support is increased, there is the potential for this ‘new’ layout method to become the norm.

References:

Andrew, R. (2016) Should I try to use the IE implementation of CSS Grid Layout. Rachel Andrew [Online] [Accessed on 07/03/2018] URL: https://rachelandrew.co.uk/archives/2016/11/26/should-i-try-to-use-the-ie-implementation-of-css-grid-layout/

Creative Bloq. (2015) 6 tips for using grids in logo design. [Online] [Accessed on 06/03/2018] URL: https://www.creativebloq.com/logo-design/6-tips-using-grids-logo-design-11513984

CSS-Tricks. (2018) A Complete Guide to Grid [Online] [Accessed on 24/02/2018] URL: https://css-tricks.com/snippets/css/complete-guide-grid/ 

W3Schools. (No Date) CSS Grid Layout Module. [Online] [Accessed on 31/01/2018] URL: https://www.w3schools.com/css/css_grid.asp
