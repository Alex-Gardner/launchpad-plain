<!-- <div class="" markdown="1"></div>
<section class="" markdown="1"></section> -->


<section class="html-starter-1-hero" markdown="1">
<div class="html-starter-hero-img-holder" markdown="1">
<img src="../assets/blog-assets/blog-raster/milada-vigerova-PE8srY2bDOs-unsplash.webp" alt="title hero" class="hero-img">
</div>

<div class="hero-text-content" markdown="1">

Alex Gardner &#183; Dec 2021

# The Ideal Structure of Your HTML Document
</div>
</section>

<div class="html-starter-1-intro-blurb" markdown="1">


HTML5 has made what was formerly the cumbersome task of creating a spec-compliant web page much more manageable. The increase in simplicity, however creates opportunities for constructing something that may be technically allowed, but can result in a host of efficiency problems and awkward pauses while the browser figures out precisely what is going on. Instead, we can take advantage of the order of our HTML declarations to make the parsing engine work to our advantage. 

<br/>


Emmet is a great first step for an HTML file started from scratch. 
The "!" abbreviation creates the following initial document structure: 
</div>

<br/>

<div class="emmet-starter-structure" markdown="1">

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
    </body>
</html>
```
<br/>
<div class="emmet-features">

This provides a number of critically important elements to start.

<br/>

* Default Language Setting
* Character Encoding for the document
* Optional tag for special instructions to older IE browsers
* Instructions for page dimensions and scaling. Sets page width to device width & sets the initial zoom level
</div>
</div>

<br/>

<div class="intro-to-roberts-technique" markdown="1">

What's not quite as clear is how to order the additional resources a modern website needs to be styled correctly (usually CSS - though other options are available) or to add various other interactions (usually with Javascript).

<br/>

The [best explanation](https://speakerdeck.com/csswizardry/get-your-head-straight) I've found thus far with regard to loading HTML resources comes from [Harry Roberts](https://twitter.com/csswizardry). The optimal order for items in HTML's \<head\> element is given by this [slide](https://speakerdeck.com/csswizardry/get-your-head-straight?slide=39):  
</div>

<br/>

<div class="slide-39-and-explanation" markdown="1">
<div class="get-your-head-straight-img-holder" markdown="1">
<img src="../assets/blog-assets/blog-raster/harry-roberts-get-your-head-straight-key-img.webp" alt="slide from Harry Roberts Get Your Head Straight Presentation. Lists the order of items in the head element - First: meta tags with charset information, http-equiv information, and viewport information. Second: Document Title. Third: preconnect items. Fourth: async scripts. Fifth: CSS that includes @import. Sixth: Synchronous Javascript. Seventh: Synchronous CSS. Eighth: preload items. Ninth: defered scripts. Tenth: prefetch and prerender items. Lastly, Everything else (SEO, meta tags, icons, Open Graph, etc.)" class="wizardry-slide">
</div>



Understanding the instructions of this slide - and more importantly the reasons behind them - could amount to thousands of dollars in value from increased responsiveness and clear benefits in improved user experience.
</div>

<br/>

<div class="further-musings" markdown="1">

The beauty of this approach is its focus on the elimination of problematic “waterfall” effects - where resources request, fetch, load, and parse in series, waiting for each operation to finish before moving on to the next.

<br/>

One approach I’m sympathetic towards is moving scripts which specifically target and manipulate DOM elements to the end of the \<body\>. This ensures all nodes necessary for the script to work have already been loaded by the time said script runs.

<br/>

Note: with multiple CSS multiple files acting on the content of a document - given the same selector specificity - the file with greatest priority should come last. In other words, CSS files which are meant to be prioritized and which override prior declarations should be placed last. 
</div>

<br/>

<div class="sample-file-structure" markdown="1">

## Sample HTML File Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>**Page Title**</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">     <!-- example preconnects for google fonts -->
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <script src="..." async></script>
    <link rel="stylesheet" href="./styles-1.css" />
    <link rel="stylesheet" href="./styles-2.css" />    <!-- these declarations override the previous -->
    <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@100..700&display=swap" rel="stylesheet"> 
    <meta name="description" content="***clear description of website***" />
    <meta name="author" content="**Author's Name**" />
    <link rel="icon" href="**link-to-icon-file**" type="image/x-icon" /> 
</head>
<body>
    ...
      <script src="**script-file.js**"></script>
</body>
</html>
```
</div>

<br/>

<div class="other-sources">

Other Sources: 

[MDN - What's in the head?](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

[MDN - Using the viewport meta tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Viewport_meta_tag)

[CSS- Tricks: Precedence in CSS](https://css-tricks.com/precedence-css-order-css-matters/)
</div>








