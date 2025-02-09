# Flexbox  

## Flex Container  

**gap**: 0 | length  creates space between items  
**justify-content**: flex-start | flex-end | center | **space-between**: | space-around | space-evenly  to align items along main axis horizontally by default  
**align-items**: stretch | flex-start | flex-end | center | baseline  To align items along cross axis vertically by default
**flex-direction**: row | row-reverse | column | column-reverse  To define which is the main axis  
**flex-wrap**: nowrap | wrap | wrap-reverse  To allow items to wrap into a new line if they are too large  
**align-content**: stretch | flex-start | flex-end | center | space-between | space-around  Only applies when there area multiple lines  

  ## flex Items  
**align-self**: auto | stretch | flex-start | flex-end | center | baseline  To overwrite align-items  
**flex-grow**: 0  | integer  To allow an element to grow when 0 = No and 1 = Yes  
**flex-shrink**: 1  | integer  To allow an element to shrink when 0 = No and 1 = Yes  
**flex-basis**: auto  | length  To define an items width instead of the width property  
**flex**: 0 1 auto  | integer  integer  length  Shorthand for flex-grow, flex-shrink, and flex-basis  
**order**: 0  | integer  Controls order of items where -1 makes them first and 1 makes it last  

# CSS Grid    

## CSS Grid Container     
**grid-template-rows**: track *  
**grid-template-columns**: track *  
**gap**: # | length  
**justify-items**: stretch | start | center | end  
**align-items**: stretch | start | center | end  
**justify-content**: start | center | end  
**align-content**: start | center | end  

## CSS Grid Items -->  
**grid-column**: start line / end line | span #  
**grid-row**: start line / end line | span #  
**justify-self**: stretch | start | center | end  
**align-self**: stretch | start | center | end  
