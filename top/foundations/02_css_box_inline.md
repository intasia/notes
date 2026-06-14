# CSS BOX AND INLINE

CSS have two box types: block and inline boxes. Defined by display: block/inline;
By default, block elements will appear on the page stacked atop each other, each new element starting on a new line.
Inline elements, will appear in line with whatever elements they are placed beside, just like a tag.
There's middle ground thou, the inline-block. Inline-block elements behave like inline elements, but with block-style padding and margin.

## Divs and spans

When adding an element that doesn't have specific semantic tag, div and span are your friend!
Div is a generic block-level container, just a rectangular boi, by default stretches accross the full width of its parent.
Div tipically used on group related elements inside page components, grouping cards, sections, sidebars and so on.

Span, a generic inline container. It sits inside a line of a text and only takes up as much space as its content.
Unlike the rectangular boi (div), it doesn't start on a new line. Likely to be used when to style or target just part of sentence.
Like highlighting hype word!

Neither div nor spans adds meaning to the content the way semantic tags do, as they exist for flexible "building blocks".
Just remember their key difference on their behaviour in the layout, and they will be your friend!

In short: 
1. div block-level element
2. span inline element

well if you're a madman, you can change their behaviour thou (i sometimes did this).

### Assignment:

1. Read Normal Flow from MDN (Done).
2. W3 Schools HTML Block and Inline Elements (in progress).
3. Digital Ocean's "Inline vs Inline-block Display in CSS (in progress).
4. Odin's Exercise 01 (done) and 02 (in progress).
5. Rework your odin's recipe based what you learn! (to do)


#### Summary from Assignment

1. Inline element can't contain a block element!
2. I understand that block elements stack and take available width, 
   inline elements flow with text and only take content width, 
   and inline-block mixes inline flow with block-like sizing.
