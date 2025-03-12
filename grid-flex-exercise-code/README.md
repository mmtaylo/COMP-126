# Exercise CSS grid and flexbox

Exercise & rules

1. See the "MakeThis.gif" and make that.
2. Only change the CSS--don't touch the HTML
3. Use CSS grid for the overall layout and Flexbox for the card/`<article>` design. See if you can do it without media queries. You will want to use repeat, auto-fill, minmax.
4. Use "rem" as the unit for margin, padding etc.

```css
main {
  display: grid;
  grid-template-columns: repeat(
    auto-fill,
    minmax(300px, 1fr)
  ); /* Keep adding new columns - even if theres is no content for them. content does not always take up full width */
  /*grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));*/ /* Don't add more columns than theres is content for. && +content "always" take full width */
  grid-gap: 1rem;
}
```

## Tutorial

_Don't go directly to the solution - try to see if you can write it on your own first! Compare your work with Jenn Simmons' solution in the video. If you are totally lost you can use the video as a tutorial. It's important that you write and understand this yourself. _

Jen Simmons' video on this very example at
https://www.youtube.com/watch?v=dQHtT47eH0M

<a href="http://www.youtube.com/watch?feature=player_embedded&v=dQHtT47eH0M" target="_blank"><img src="http://img.youtube.com/vi/dQHtT47eH0M/0.jpg" 
alt="Jen Simmons showing how to use flexbox and grid combined in web layout" width="240" height="180" border="10" /></a>
