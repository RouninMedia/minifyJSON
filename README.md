# minifyJSON
minifyJSON is a function which strips all whitespace (outside double-quotes) from a JSON string. An Ashiva Component.

# SVG to Data URI

The function `SVGtoDataURI(svg)` converts any SVG into a **Data URI**.

Before it does so, it verifies that the string it has been given to process is a **valid SVG**.

______

## Step 1

The function `SVGtoDataURI(svg)` verifies that the string passed to the function:

 - has a valid **SVG Namespace**
 - represents **well-formed XML**

If either or both conditions are not met, the `SVGtoDataURI(svg)` function will return a verbose error detailing how the string may be fixed.

## Step 2

If both the conditions above are met, the `SVGtoDataURI(svg)` function returns the validated SVG as a **Data URI**.

_____

## `SVGtoDataURI(svg)` Function

```
