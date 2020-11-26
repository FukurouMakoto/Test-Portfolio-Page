There are three main ways to move items around with CSS:

justify-content: 
    aligns items horizontally and accepts the following values:
    flex-start: 
        Items align to the left side of the container.
    flex-end: 
        Items align to the right side of the container. 
    center: 
        Items align to the center of the container.
    space-between: 
        Items display with equal spacing between them.
    space-around:
        Items display with equal spacing around them. 

align-items: 
    aligns items vertically and accepts the following values:
    flex-start: 
        Items align to the top of the container.
    flex-end: 
        Items align to the bottom of the container. 
    center: 
        Items align to the vertical center of the container.
    baseline: 
        Items display at the baseline of the container.
    stretch: 
        Items are stretched to fit the container. 

flex-direction: 
    defines the direction items are placed in the container.
    row: 
        Items are placed the same as the text direction. 
    row-reverse: 
        Items are placed opposite to the text direction. 
    column: 
        Items are placed top to bottom.
    column-reverse: 
        Items are placed bottom to top. 

order: 
    Allows you to reorder specific items in a container as opposed to working with the entire group. 
    Uses positive & negative integers in order to move everything.
align-self: 
    Similarly to order, allows you to move specific individual items as opposed to the entire container. 
    Uses the same values as align-items.

flex-wrap:
    nowrap: Every item is fit to a single line.
    wrap: Items wrap around to additional lines.
    wrap-reverse: Items wrap around to additional lines in reverse.

flex-flow: 
    A combination of flex-direction and flex-wrap. Accepts the value of one of the two properties seperated by a space.

align-content: 
    Used to set how multiple lines are spaced apart from each other. You may confuse it with align-items, but align-content determines the spacing between lines, while align-items determines how the items as a whole are aligned within the container. Thus when there is only one line, align-content has no effect. 
    Uses the following values:
    flex-start: Lines are packed at the top of the container.
    flex-end: Lines are packed at the bottom of the container.
    center: Lines are packed at the vertical center of the container.
    space-between: Lines display with equal spacing between them.
    space-around: Lines display with equal spacing around them. 
    stretch: Lines are stretched to fit the container.