# Tentaur Tent Product Page

##### CSS - A tent product page website

#### By Cheryl Frankenfield, 11/17/17

## Description

_This website is a demonstration of using CSS styles and practices including centering, the box model, floats, tables, selectors, pseudo elements and classes, and positioning._

## Setup/Installation Requirements

* Navigate to your terminal.
* Perform Git clone command on the repo [here.](https://github.com/CherylFrankenfield/product-page.git)
* Perform Git atom . command to open all files in repo.
* View index.html in browser.
* No other setup or install necessary.
* Or [click here](link) to view in browser now.

## Specs

_The site will display a single-page site that showcases a product for sale._

_The site includes at least one centered element._
* _Example: Review/quote text is centered._

_The site includes a list or summary of features._
* _Example: Product details list is included._

_The site includes one large image with an absolutely positioned caption._
* _Example: The text, price and button section is absolutely positioned on hero image._

_The site includes one table styled with CSS._
* _Example: Materials and measurements table is included._

_The site includes a gallery of images._
* _Example: Gallery of smaller images is included._

## CSS Elements Used

| Term                | Description                                                                         | Implementation  |
| --------------------|:-----------------------------------------------------------------------------------:|----------------:|
| Border-box          | This property tells the browser what the sizing properties (w,h) should include.    | By setting the default of my page to border-box: box-sizing, the elements' will act more true to size and will include my border and padding.            |
| Float               | This property specifies that an element should be placed along the left or right side of its container, allowing text and inline elements to wrap around it.| I used float a few times here. In one case, I floated a dropcap on the left of the first paragraph text. I also used float on my button so it would fit in the right-hand corner of my container. |                                                                                   
| Display: Block      | A block element occupies the entire space of its parent element or container. (div)| I used a few block elements, like divs and paragraph tags, though did not make sure of display:block in my styles. |                       
| Display: Inline     | An inline element is displayed inside the current block on the same line. (span) | Here I used an inline display style in my navigation bar to fix elements in a list in a span, rather than a block. |
| Centered Content    | You can center content with CSS, for example:(text-align: center;) or with positioning (absolute and relative).| I vertically and horizontally centered my review quote text at the footer of the page, with the paragraph tag absolutely centered within the parent div. |
| Pseudo-Element      | This property allows you to target sub-parts of an element. (:first-letter) | I used a first-letter selector to help create a dropcap style.  |                        
| Pseudo-Class        | This property allows you to target complete elements or states. (id or a:hover) | In this page, I used a hover color style on my button. |                              
| Clear-Fix           | This property allows you to fix collapsed parents when you float elements.| I used the clear:both; property and overflow:auto; on the page to clear the floats I used. |            
| Positional Selector | This property allows you to select elements based on position. (:nth-child(2)) | I used the nth-child selector on the table data and table header elements to create a border style.|
| Selector Combinator | This property allows you to combine selectors. (child selector (>) ) | Here I used a descendent selector on class .hero-text with the descendent of <ul> and descendent of <li>:hover. |

## Known Bugs

_On my navigation bar, on hover over, it's selecting the whole inline block, but I'd like it to select only the text within the list._

## Support and contact details

_If you have any issues, questions, ideas or concerns, please contact me._

## Technologies Used

* HTML
* CSS

### License

*This is open source so feel free to grab and use.*

Copyright (c) 2017 **_Cheryl Frankenfield_**
