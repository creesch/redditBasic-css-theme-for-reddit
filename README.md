redditBasic-css-theme-for-reddit
================================

A subreddit theme to be used by subreddit owners on www.reddit.com


## Installation

Grab the css from [github](https://github.com/creesch/redditBasic-css-theme-for-reddit), and download the following sprites: 


1. [sprite-icon-16.png](https://raw.githubusercontent.com/creesch/FlatBlue-css-theme-for-reddit/master/sprite-icon-16.png)
2. [sprite-icon-32.png](https://raw.githubusercontent.com/creesch/FlatBlue-css-theme-for-reddit/master/sprite-icon-32.png)

Go to /r/<yoursubreddit>/about/stylesheet 

You'll find one text area where you can paste the css and below that options for uploading the images. 

*Upload the sprite images before saving the css*

To tell RES that this style supports nightmode you'll have to add the following to your sidebar: 

    [](#/RES-nightModeCompatible)[](#/RES_SR_Config/NightModeCompatible) 

That's about it for a basic installation. 

### css? 

If you haven't got the slightest clue as to what css is and how it works I really do recommend reading up on it. Even if you only plan to do some basic adjustments it helps a great deal if you have a basic grasp of the basics: 

- [Beginners guide to css](http://www.htmldog.com/guides/css/beginner/)
- /r/csshelp 

### I still have trouble finding pages where I need to put it. 

Have a look at my ["Creating and moderating a subreddit 101"](http://www.reddit.com/r/creesch/wiki/mod101) guide. 


## Icons 
Icons are very simply to use, simply do the following 

    [](#icon-android)
Which will turn into [](#icon-android)
A complete list of the available icons can be found [here](/r/redditBasic/w/icons) 

## Colored boxes in your sidebar

    ###### Red header
    >
    > Red box
    
    #### Green header
    >
    > Green box
    
    ##### Blue box
    >
    > Blue box

## Spoilers 

`[This is a spoiler](#spoiler)`     
[This is a spoiler](#spoiler)  

## Changing font sizes

With this theme it is no longer needed to search the entire css for all size declarations! Simply look for the one block of code that handles ***all*** font sizes. 

## Header size

When adjusting the header height you also will need to adjust some other positioning. For your convenience those lines of codes are positioned directly after the code for the header. 

## Required images

- header-blue.png 
- reddit-res-sprite-icons.png
- sprite-icon-32.png (white and dark versions are available)
- sprite-icon-16.png

## Link flairs

Link flairs couldn't be more easier. By default there are 7 premade colored flairs included which are alphabetically named starting from a and ending with g. Simply use those in the class field and you will see that each correspondents with a color.

