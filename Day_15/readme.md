# Day 15 - Media Query

## Syntax

```CSS
/* 0 */
@media `media-type` () {
  
}

/* 1 */
@media (){ //if leave blank or don't mention any media-type that means we are targeting all.

}
// or can use `all`
@media all (){ 

}

/* 2 */

@media (max-width:660px){ /* 660px or smaller */

}


@media (min-width:660px){ /* 660px or larger */

}

/* 3 */
@media (min-width:value) and (min-width:value){ 

}
```

## Mobile First

When we crete mobile layout first then we use min-width to create layout for desktop or larger devices.

## Desktop First

When we crete desktop layout first then we use max-width to create layout for mobile or smaller devices.

## Resources

<https://www.freecodecamp.org/news/the-100-correct-way-to-do-css-breakpoints-88d6a5ba1862/>

The tl;dr of the article: Use --

- 600px,
- 900px,
- 1200px,
- and 1800px
- if you plan on giving the giant-monitor people something special.
