<!----Writeup part for Box-Model---------->

All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout.
Box-Model consists of Padding,border,margin ,width,height and the content.

Explanation of the different parts:
 Content - The content of the box, where text and images appear
 Padding - Clears an area around the content. The padding is transparent
 Border - A border that goes around the padding and content
 Margin - Clears an area outside the border. The margin
 is transparent.

Width&height of an element:

 When you set the width and height properties of an element with CSS, you just set the width and height of the content area. To calculate the full size of an element, you must also add padding, borders and margins.

The total width of an element should be calculated like this:

 Total element width = width + left padding + right padding + left border + right border + left margin + right margin

 The total height of an element should be calculated like this:

 Total element height = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin