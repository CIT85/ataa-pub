# Week 4 - Chp 1 thru 51
## What is cascading
it means CSS rules are applied based on order and importance

## external, internal, inline sytles
external is css in seperate file and is the most common used
example <link rel="stylesheet" href="style.css">

internal is css written inside a <style> tag in the HTML 

inline is written directly in the element 
example <p style="color; red; ">Hello</p>

## CSS Ruleset
two types of rulesets:
Selector: in the HTML element you want to style 
Decleration: Inside curly braces {} 

Each decleration has a property such as a color and a value such as blue

Example 
p {
    color; red;
}

## Selectors
Id selector targets specific element with unique id
it uses the # symbol in css like #main-title {color: red;}
it should only be used once per page

the universal selector targets all elements
it is usefull for resetting styles

# specificity

Determines which CSS rule wins when there are multiple rules
More specific ones such as id's override general ones like classes or elements
inline styles are the most specific

## Inheritance
some properties such as font family and color are inherited from parent elements

# Chrome DevTool
Right click> inspect element.
Use styles to see what Css is applied andd what rules are overidden.

# DRY
Avoiding to repeat yourself in order to have a clean organized code
use classes to group common styles and reduce repetition
 # !important and why to avoid
 It forces a style to appyl, overriding everything else
it should be used only when necessary as it breaks the cascade. 
it breaks the natural order of styles 
other developers may not understand why a style isnt working unless they spot it

# colors

There are 4 different ways to write colors:
Color name: red, blue black 
Hex code:#000000, #ffffff
rgb: rgb(255,0,0) (RED GREEN BLACK)
hsl: hsl(o,100%,50%) (HUE SATURATION LIGHTNESS)

with VS code color picker you can choose colors visually and adjust trancparenct and see a preview before applying

good color contrast improves readability and accesibilty of the page 
low contrast= hard to read
coolors.com is great for contrast checking and palettes

# values and units

px: pixels are in fixed size they dont change based on user sertting or screens ize

rem: root em is relative to the root element and is good for concistency
1rem=font size of <html>

em:relative to the parent elements font size and is useful for spacing

ch:character unit- based on the width of the 0 character 
40ch=40 characters wide.

## vw and vh
vw is viewport width 1vw is 1% of the browser window widht
vh is vuewport height 1vh is 1% of the browser windows height 

# intro to box model 
content is actual text or image
padding is space around content
border is the otline around the padding
margin is the space outside the border

# longhand shorthand margin
longhand lets you see each side individually
short hand is cleaner and faster 

# padding and border notation 
padding adds space insiide the element, between content
border outlines the element 


