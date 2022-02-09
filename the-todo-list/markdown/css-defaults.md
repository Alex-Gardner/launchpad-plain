<!-- <div class="" markdown="1"></div> -->
<!-- <sectsion class="" markdown="1"></section> -->


<!-- &#38; -->

<section class="css-reset-hero" markdown="1">
<div class="hero-layout-holder" markdown="1">

Alex Gardner &#183; Dec 2021

# CSS defaults for <br/><span class="emphasis-lettering">conformity</span><br/> & ease of use

<span class="homage" markdown="1">

\*In homage to the eternal [CSS meme](https://css-tricks.com/css-is-awesome/)
</span>
</div>
</section>

<br>

<section class="css-reset-description" markdown="1">

In my view, the [best modern CSS reset is that by Josh W Comeau](https://www.joshwcomeau.com/css/custom-css-reset/). It touches on  the most commonly used elements in web development, and also keeps an eye peeled for accessibility issues. The article itself is an amazing tour de force of insights into browsers, tradeoffs vs other approaches, and clear explanations of complex CSS concepts.

<br/>

Below is an exact copy of his custom CSS reset with two small additions. Firstly, default [button styles](https://ishadeed.com/article/styling-the-good-old-button/) for browsers are almost never reasonable designs for typical use cases. I’ve added a small reset to a simple default style worth building upon. Secondly, in the modern world of intrinsic web design, having a typography system that scales with the user’s viewport size is a firm requirement. I’ve also included a simple fluid typographic system which works reasonably well. Within the body of the site, font-size is set in rem units. Issues may appear on the margin - I’ll be sure to note them as encountered. [Chris Coyier](https://css-tricks.com/notes-on-josh-comeaus-custom-css-reset/) has recently written an interesting post about Josh's reset (and normalization more generally) 
</section>

<br/>

<section class="css-reset-code" markdown="1">

```css
/*
  Josh's Custom CSS Reset
  https://www.joshwcomeau.com/css/custom-css-reset/
*/
*, *::before, *::after {
  box-sizing: border-box;
}
* {
  margin: 0;
}
html, body {
  height: 100%;
}
body {
  line-height: 1.5;
  -webkit-font-smoothing: antialiased;
}
img, picture, video, canvas, svg {
  display: block;
  max-width: 100%;
}
input, button, textarea, select {
  font: inherit;
}
p, h1, h2, h3, h4, h5, h6 {
  overflow-wrap: break-word;
}
#root, #__next {
  isolation: isolate;
}


/*  Button Styles Reset */
button {
  appearance: none;
  -webkit-appearance: none;
   -moz-appearance: none;
  border: none;
  border-radius: 0;
  background-color: #ababab;
  color: inherit;
}

/*  Quick Fluid Typography */
html {
    font-size: clamp(16px, 2.2vw, 25px);
}

```
</section>

