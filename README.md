# html-framework-mamaev
My first HTML framework.

CSS classes:

"container" is an adaptive container. Shrinks by width to 900px if viewport width is between 1200px and 993px, to 744px if viewport width is between 992px and 769px, to 576px if viewport width if 768px or less.

"row" is a container for columns.

".col-4", ".col-sm-4", ".col-md-4", ".col-lg-4" are adaptive columns which take up a third of the viewport's width. Adaptive property for columns means they lose their float attribute when the viewport width is less than a certain number of pixels. The smallest class of columns never transform; the others do at viewport width breakpoints of 768px, 992px and 1200px, respectively.

"clearfix" inserts a clearfix pseudoelement after the affected element, which assigns "clear" property to floats in both directions.

"pull-left" and "pull-right" are for assigning elements the float property.

"flex-row" and "flex-column" use the flexbox module, they arrange the element's children in a row or column, respectively. The element itself becomes a flexbox container, and the following attributes can be applied.
"space-between" makes the space be distributed evenly among the children. "y-center" allows for centering of elements along the cross axis (doesn't work if there's just one line of flex items). "x-start" and "x-end" anchor the items to the beginning and the end of the main axis, respectively.

"square" and "square-sm" are graphic objects for demonstration.

The set of "margin-?px" and "padding-?px" are used to add margins and padding.g
