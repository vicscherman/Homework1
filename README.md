# Horiseon SEO

Our job here was to clean up some existing code to both meet accessibility standards, and be optimized for search engines

## Work to be done
* We need to replace div elements with semantic HTML
* We need to ensure the HTML elements have a logical structure
* We need to make sure our images have ALT attributes
* We need to make sure our headings follow in sequential order (h1, h2, h3 etc)
* We need to give our site a concise, descriptive title

## What I did

1. First, I went through all the images in the html, and added alt tags to the images. This is done by adding alt like in the following example.
    
    ```
    <img src="example" ">

    becomes

    <img src="example" alt="alternate text">
    ```

   I also altered some of the image tags to be self closing instead of ```<img></img>``` to be more in line with modern standards

2. With that out of the way, I wanted to address some of the semantic elements. I added the following semantic tags:

1. ```<header>``` for the page header
2. ```<nav>``` for the navigational links within the header
3. ```<article> ```for the main info section of the site, with ```<section> ```for the various elements inside
4. ```<aside> ```for the side bar
5.  ```<footer> ```for the footer

## CSS work

With that out of the way, I went into the CSS file, and altered the selectors to be in line with the new semantic HTML elements. By doing so I was able to get rid of a lot of duplicate code because multiple elements with unique class IDs were now falling under single classes. 


## Some Helpful links
[CSS on w3schools](https://www.w3schools.com/css/default.asp)
[Markdown cheatsheet] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Special Thanks (in no particular order)
* My study group
* Fil
* Daniel
* My cats

## License

Copyright (c) 2020] [Victor Scherman]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.