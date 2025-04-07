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
