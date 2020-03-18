To think about CSS is to think that there is an invisible box around every element.


//Box Model
    content - text
    padding - clears area arouund the content. Is transparent
    Border - Around the content and padding
    margin - arounf the border and is transparent

    `*{universal selector
    }`

Example styles:
Boxes - width, height
    -borders (color width)
    -BG color
    -position in browser window

Text -typeface
    -size
    -color

Specific -style lists tables and forms

Selector ---> "p" {
        Property--->  font-family: Arial <--- Value>;         <----Declaration
}

`* {}` Universal Selector
`h1, h2, h3 {}` Type selector
`.note {}` Class Selector. This targets any element whose class attribute has a value of "note"
`p.note {}` Class selector Targets only <p> elements whose class attribute has a value of note
`#introduction {}` ID selector Targets the element whose id attribute is introduction
`li>a {}` Child selector targets any element that is nested in another element. In the example, its targeting an anchor tag within a list item.
`p a {}` Matches an element that is a descendent of another specified element (not just a direct child of that element) in this case its an anchor tag that is inside a `<p>`
`h1+p {}` Adjacent sibling selector. Matches an element thatt is next sibling of another. This case mathces the first `<p>` in an `<h1>` element but not the others.
`h1~p {}` General sibling selector. Basically the same as adjacent but includes all the `<p>`'s in this case.

RGB is Red Green Blue and the value is portrayed in that order ex. (100,100,90)

`/* insert comment here that wont be read by the browser */`

you can use opacity to select colors as a value between 0.0 and 1.0 and will be applied to the element it is aattched to


Below is example of CSS code for multiple paragraphs 

`<!DOCTYPE html>
<html>
<head>
 <title>Color</title>
 <style type="text/css">
 body {
 background-color: silver;
 color: white;
 padding: 20px;
 font-family: Arial, Verdana, sans-serif;}
 h1 {
 background-color: #ffffff;
 background-color: hsla(0,100%,100%,0.5);
 color: #64645A;
 padding: inherit;}
 p {
 padding: 5px;
 margin: 0px;}
 p.zero {
 background-color: rgb(238,62,128);}
 p.one {
 background-color: rgb(244,90,139);}
 p.two {
 background-color: rgb(243,106,152);}
 p.three {
 background-color: rgb(244,123,166);}
 p.four {
 background-color: rgb(245,140,178);}
 p.five {
 background-color: rgb(246,159,192);}
 p.six {
 background-color: rgb(245,176,204);}
 p.seven {
 background-color: rgb(0,187,136);}

 </style>
</head>
<body>
 <h1>pH Scale</h1>
 <p class="fourteen">14.0 VERY ALKALINE</p>
 <p class="thirteen">13.0</p>
 <p class="twelve">12.0</p>
 <p class="eleven">11.0</p>
 <p class="ten">10.0</p>
 <p class="nine">9.0</p>
 <p class="eight">8.0</p>
 <p class="seven">7.0 NEUTRAL</p>
 <p class="six">6.0</p>
 <p class="five">5.0</p>
 <p class="four">4.0</p>
 <p class="three">3.0</p>
 <p class="two">2.0</p>
 <p class="one">1.0</p>
 <p class="zero">0.0 VERY ACID</p>
</body>
</html>`