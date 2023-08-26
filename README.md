# theme-example
A brief example of creating different website themes


First we used JavaScript to add a class attribute on our html element (We don’t have direct access to the html element in the HTML tab on codepen, but you should be able to see the class being applied in the browser’s inspector) so that our page has a default theme. Next in our CSS we created two scopes for our custom properties on the :root selector, one for when our html (or root) element has a class of dark and another for when it has a class of light. Our other selectors then use the values of any custom properties depending on which class is currently present on our root element.

