# jimi
---

Simplified basic grid and typography styles. Standard reset, classes, browser fixes that we all use, and variables for consistent color usage. 

For something more complete, use Bootstrap or Foundation.

In alpha phase. Updating personal site to use this in order to replace Bootstrap. Will commit to beta phase upon completion.

## Grid
---

This grid uses a Flexbox grid that shares relation to Bootstrap and Foundation's grid. It is simplified for basic needs. Includes a few `justify-` helper classes.

### Breakpoints
---
Large Screens `l` (not within a media query)  
Extra Large Screens `xl` (Media Query begins with `min-width:1441px`)  
Medium Screens (laptop/tablets) `m` (Media Query begins with `max-width:1068px`)  
Small Screens (Phones/small tablets) `s` (Media query begins with `max-width:734px`)

### Internet Explorer / Edge
---
This uses Flexbox (IE10+ w/ `-ms` prefix) and `--var` in the CSS, which is not supported in IE at all and only used in Edge 16+. IE11 came out in 2011, unless you have a very specific use case to have this site work for IE11 and back, this should work in all modern browsers. If you've got the unlucky opportunity to have one of those specific use cases, just code like it's 2005 and have fun.  

## Copyright and license

Copyright 2020 *jwrightmedia, LLC*, All Rights Reserved. 
Let's be honest, this is basic CSS that most developers use. The copyright is more just don't steal the name and give credit where credit is due for the organization. 