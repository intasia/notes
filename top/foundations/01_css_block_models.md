# Box Models

Apparently almost everything on html is a rectangle, they just shaped in certain way to make a layout.
This concept is super important, missing this concepts will hurt later on.

Generally we can make a layout by manipulating those rectangles, by:
1. Sizing them.
2. Manage the space between them, using padding, border and margin.

** Managing the space between them? **
1. Padding, the space between the border of a box and the content of the box. 
   Basically mean space the inside to the border.
2. Margin, space between the borders of a box and the borders of adjacent boxes. 
   Basically mean space between boxes by its border?
3. Border, Border is the line/thickness around the padding and content. It sits between padding and margin..
   Its him, the border.

** Assignment To Do**

1. Learn CSS Box Model in 8 minutes, https://www.youtube.com/watch?v=rIO5326FgPE. (Done)
2. box-sizing: border-box (EASY!), https://www.youtube.com/watch?v=HdZHcFWcAd8. (Done)
3. MDN box model documentation, https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model. (Done)
4. The CSS tricks page on margins, https://css-tricks.com/almanac/properties/m/margin/. (To Do)

** Note for Each Assignment **

1. Use box-sizing: border-box to account padding, border, and content to be accounted by height and width. 
   Just use it to * (global) selector, so every element using border-box sizing instead, why the heck its not the default?
2. Chrome/browser devtools is your friend! it can check the box-models diagram.
3. Margin is more like space between boxes, so it doesnt count to box-sizing. 
   The highest margin is winning on spacing when adjacent boxes have defined different margin number.

** Knowledge Check **
1. From inside to outside, what is the order of box-model properties?
   A: Content, Padding, Border, Margin
2. What does the box-sizing CSS property do?
   A: Property to calculate which box-model properties sizes to account for. 
      Content-Box: The sizing will be Border + Padding + Content (which decided by width and height)
      Border-Box: The sizing will acount padding, border and content altogether. 
3. What the difference between the standard and alternative box model.
   A: already answered above
4. Would you use margin or padding to create more space between 2 elements?
   A: i would use margin, since its actually the space between boxes.
5. Would you use margin or padding to create more space between the content os an element and its border?
   A: i would use padding, its used to adjust space between content and its border.
6. Would you user margin or padding if you wanted two elements to overlap each other?
   A: i would use margin? since its the space between boxes, so we could just set it to minus?.
7. How do you set the alternative box model for all of your element?
   A: use box-sizing: border-box on * selector.
8. How do you center an element horizontally?
   A: use margin auto?





