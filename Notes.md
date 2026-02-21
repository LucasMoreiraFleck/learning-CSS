In this first commit, I am exploring the concepts of the CSS box model:

    All the HTML elements are considered as a box.
    All boxes have certain properties, like content, height, width, margin and others.

Now i will learn about those properties:

    The display property controls how boxes are presented on your site.
    More details are on index.html.

    The border will style the border of your box.
    More details are on style.css.

    The width and height will determine the width and the height of the box.
    More details are on style.css and index.html.

    The margin will determine the margin of the box.
    More details are on style.css and index.html.

    The padding will handle the internal filling of the box.
    More details are on style.css and index.html.

Next, I will be learning about fonts and texts on CSS:

    The property font-family will be altering the fonts of your text.
    More details on style.css and index.html.

    The property font-size will be altering the size of your texts.
    More details on style.css and index.html.

    The properties font-weight and font-style are just to change your text to bold or italic.

    The property color will be altering the color of your texts.

    The property text-transform will convert the text to uppercase, lowercase, or capitalize initials.

    The text-decoration shorthand property sets the appearance of decorative lines on text.

    The text-align will define where your text will be aligned.

    The line-height will define the height of the lines on your text.

Now I’m going to learn about colors and backgrounds, but I’ll just note down the property names.

    background-color

    background-image

    background-repeat

    background-position

    background-size

This time will learn about layouts on CSS

    The position property is used to position boxes within the website. Its values are very important; therefore, I will describe them below:

    Static: This value is the default for this property, so every element has this position by default.

    Relative: this value makes the offset relative to itself; however, it still respects the normal flow.

    Absolute: This value ignores the normal flow and is positioned relative to its nearest positioned ancestor (containing block). If no positioned ancestors exist, it is positioned relative to the initial containing block (the viewport/page).

    Fixed: This value fixes the element to the screen relative to the initial containing block (the viewport). It stays in a specific position even after scrolling the page.

    Sticky: This value is relative to the nearest scrolling ancestor. When the container has overflow: scroll (or auto), the element becomes fixed within that container's boundaries as you scroll.

    
Now im learning about variables

    CSS Variables (Custom Properties) allow you to store specific values to be reused throughout your stylesheet.

    To create a variable, you only need to use two dashes (--) followed by the variable name. A variable can contain any value.

    To use a variable, use the var() function followed by the variable name: var(--variable-name).

    Variables follow the CSS cascade. When using a variable, the value is inherited from the nearest ancestor in the hierarchy. In this example, the div will inherit the value from main instead of body.



