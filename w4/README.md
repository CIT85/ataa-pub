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
