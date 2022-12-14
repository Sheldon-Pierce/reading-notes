[Home](../README.md)

# CSS

## What is CSS?

CSS (Cascading Style Sheets) allows you to create great-looking web pages. CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc. CSS can be used for very basic document text styling — for example, for changing the color and size of headings and links. It can be used to create a layout — for example, turning a single column of text into a layout with a main content area and a sidebar for related information. It can even be used for effects such as animation.

## CSS Syntax

CSS is a rule-based language — you define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

For example, you can decide to have the main heading on your page to be shown as large red text. The following code shows a very simple CSS rule that would achieve the styling described above:

h1 {
  color: red;
  font-size: 5em;
}

- In the above example, the CSS rule opens with a selector. This selects the HTML element that we are going to style. In this case, we are styling level one headings (\<h1>).
- We then have a set of curly braces { }.
- Inside the braces will be one or more declarations, which take the form of property and value pairs. We specify the property (color in the above example) before the colon, and we specify the value of the property after the colon (red in this example).
- This example contains two declarations, one for color and the other for font-size. Each pair specifies a property of the element(s) we are selecting (\<h1> in this case), then a value that we'd like to give the property.

CSS properties have different allowable values, depending on which property is being specified. In our example, we have the color property, which can take various color values. We also have the font-size property. This property can take various size units as a value.

A CSS stylesheet will contain many such rules, written one after the other.

h1 {
  color: red;
  font-size: 5em;
}

p {
  color: black;
}

You will find that you quickly learn some values, whereas others you will need to look up. The individual property pages on MDN give you a quick way to look up properties and their values when you forget or when you want to know what else you can use as a value. [-1]

## How To Add CSS

There are three ways of inserting a style sheet:

External CSS

- With an external style sheet, you can change the look of an entire website by changing just one file!
Each HTML page must include a reference to the external style sheet file inside the \<link> element, inside the head section.

- \<link rel="stylesheet" href="mystyle.css">

Internal CSS

- An internal style sheet may be used if one single HTML page has a unique style. The internal style is defined inside the \<style> element, inside the head section.

Inline CSS

- An inline style may be used to apply a unique style for a single element.
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

- \<h1 style="color:blue;text-align:center;">This is a heading</h1>

- \<p style="color:red;">This is a paragraph.</p>

## Cascading Order

What style will be used when there is more than one style specified for an HTML element?

All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

- Inline style (inside an HTML element)
- External and internal style sheets (in the head section)
- Browser default

So, an inline style has the highest priority, and will override external and internal styles and browser defaults.[-2]

[-1]: https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS

[-2]: https://www.w3schools.com/css/css_howto.asp
