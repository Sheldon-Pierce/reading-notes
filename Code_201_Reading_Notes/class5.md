[Home](../README.md)

## HTML Media

The next attribute we'll look at is alt. Its value is supposed to be a textual description of the image, for use in situations where the image cannot be seen/displayed or takes a long time to render because of a slow internet connection.

From an accessibility viewpoint, captions and alt text have distinct roles. Captions benefit even people who can see the image, whereas alt text provides the same functionality as an absent image. Therefore, captions and alt text shouldn't just say the same thing, because they both appear when the image is gone. Try turning images off in your browser and see how it looks.

A figure doesn't have to be an image. It is an independent unit of content that:

- Expresses your meaning in a compact, easy-to-grasp way.
- Could go in several places in the page's linear flow.
- Provides essential information supporting the main text.
A figure could be several images, a code snippet, audio, video, equations, a table, or something else.

gif - Good choice for simple images and animations. Prefer PNG for lossless and indexed still images, and consider WebP, AVIF or APNG for animation sequences.
Supported: Chrome, Edge, Firefox, IE, Opera, Safari.

svg - Vector image format; ideal for user interface elements, icons, diagrams, etc., that must be drawn accurately at different sizes.
Support: Chrome, Edge, Firefox, IE, Opera, Safari.

## CSS

Foreground colors would essentially be on top of the container, so the color of text or a link would be foreground colors that do not effect the container. Background colors would be the color of the container which contains items, and the items sit on top of this color.

You would use color to spice up the website and give it some character. You can also use color to section off areas in your code and make it stand out.

### Web safe fonts

Speaking of font availability, there are only a certain number of fonts that are generally available across all systems and can therefore be used without much worry. These are the so-called web safe fonts.

Most of the time, as web developers we want to have more specific control over the fonts used to display our text content. The problem is to find a way to know which font is available on the computer used to see our web pages. There is no way to know this in every case, but the web safe fonts are known to be available on nearly all instances of the most used operating systems (Windows, macOS, the most common Linux distributions, Android, and iOS).

The font-size of an element is inherited from that element's parent element. This all starts with the root element of the entire document — \<html> — the standard font-size of which is set to 16px across browsers.

font-style: Used to turn italic text on or off. Possible values are as follows (you'll rarely use this, unless you want to turn some italic styling off for some reason):
normal: Sets the text to the normal font (turns existing italics off).
italic: Sets the text to use the italic version of the font, if available; if not, it will simulate italics with oblique instead.
oblique: Sets the text to use a simulated version of an italic font, created by slanting the normal version.

font-weight: Sets how bold the text is. This has many values available in case you have many font variants available (such as -light, -normal, -bold, -extrabold, -black, etc.), but realistically you'll rarely use any of them except for normal and bold:
normal, bold: Normal and bold font weight.
lighter, bolder: Sets the current element's boldness to be one step lighter or heavier than its parent element's boldness.
100 – 900: Numeric boldness values that provide finer grained control than the above keywords, if needed.

The letter-spacing and word-spacing properties allow you to set the spacing between letters and words in your text. You won't use these very often, but might find a use for them to obtain a specific look, or to improve the legibility of a particularly dense font.

## Things I want to know more about