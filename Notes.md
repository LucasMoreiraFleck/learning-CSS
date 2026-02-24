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

Learning about pseudo-classes

    A CSS pseudo-class is a keyword added to a selector that lets you style a specific state of the selected element(s). For example, the pseudo-class :hover can be used to select a button when a user's pointer hovers over the button and this selected button can then be styled.

    The :hover pseudo-class is an interaction pseudo-class; therefore, it is activated whenever the user moves the cursor over an element.

    The :not() pseudo-class is a functional pseudo-class used to select elements that do not match the selector provided within the parentheses. It applies the defined styles to all elements except those specified.

    The :has() pseudo-class is a functional pseudo-class that allows an element to be styled based on its descendants or state. For example, you can style a parent element only when a child div is being hovered over.

    The :root pseudo-class is a structural pseudo-class used to define the root context of your website. For example, it can be used to set a specific font or global variables to be applied throughout the entire site.

Learning about pseudo-elements

    The ::first-letter pseudo-element is used to apply styles specifically to the first letter of the first line of a block-level element.

    The ::before pseudo-element is used to insert and style content before the actual content of an element.

    The ::after pseudo-element is used to insert and style content after the actual content of an element.

Learning about flexbox

    The flex value for the display property creates a flex container based on two axes. The 'Main Axis' is horizontal by default (left to right), and the 'Cross Axis' is vertical (top to bottom). In this layout, items are distributed and aligned along the main axis.

    The flex-direction property changes the orientation of the main axis within a flex container.

    The justify-content property defines how flex items are distributed and aligned along the main axis of the flex container.

    The align-items property defines the default alignment for flex items along the cross axis of the flex container.

    The flex-wrap property allows flex items to wrap onto multiple lines if they exceed the container's width. By default, it creates new rows (multi-line container), which can make using justify-content and align-items alone insufficient for controlling the space between these lines.

    The flex-basis property defines the initial main size of a flex item before the remaining space is distributed according to the flex factors.

    The flex-grow property sets the flex grow factor, which specifies how much of the flex container's positive free space, if any, should be assigned to the flex item's main size.

    The flex-shrink property defines the ability of a flex item to shrink if necessary. Its default value is 1, meaning shrinking is enabled. Setting it to 0 prevents the item from shrinking below its initial size.

    

