'''
CSSColoring

Overview: 
- This CSS stylesheet provides styling rules for a web page. It includes styles for headings, container elements, and in the specific context of the index.html file, it contains various design elements referred to as markers, caps, and sleeves. Additionally, it contains color-specific styles for elements with classes .red, .green, and .blue.

Author: 
- Omar Darwish

Date Created:
- 1/17/24

Styles Description: 
- Heading (h1)
  - text-align: center;: Centers the text in <h1> elements.
- Container: 
  - background-color: rgb(255, 255, 255);: Sets the background color of elements with the .container class to white.
  - padding: 10px 0;: Adds padding of 10 pixels to the top and bottom of the .container elements.
- Marker:
  - width: 200px;: Sets the width of .marker elements to 200 pixels.
  - height: 25px;: Sets the height of .marker elements to 25 pixels.
  - margin: 10px auto;: Applies a margin of 10 pixels on all sides and automatically centers the .marker elements           
    horizontally within their parent container.
- Cap:
  - width: 60px;: Sets the width of .cap elements to 60 pixels.
  - height: 25px;: Sets the height of .cap elements to 25 pixels.
- Sleeve
  - width: 110px;: Sets the width of .sleeve elements to 110 pixels.
  - height: 25px;: Sets the height of .sleeve elements to 25 pixels.
  - background-color: rgba(255, 255, 255, 0.5);: Sets a semi-transparent white background color to .sleeve elements.
  - border-left: 10px double rgba(0, 0, 0, 0.75);: Adds a double-lined border to the left side of .sleeve elements.
- Cap and Sleeve:
  - display: inline-block;: Sets the display of .cap and .sleeve elements to inline-block, allowing them to sit next to each     other in line.
- Color Classes (Red, Green, Blue):
  - .red, .green, .blue: Define background gradients and box shadows for elements with these classes, applying different     
     color schemes for red, green, and blue variations.
Usage:
- To use this stylesheet, link it within the <head> section of your HTML document. Ensure that your HTML elements have the 
  corresponding class names to apply these styles.

Contents:
- Along with the style.css file, the repository also contains the example that the file was used and implemented towards,      the index.html file. 
