[Home](../README.md)

# Wireframing and HTML

## What is wireframing?

Wireframing is a practice used by designers which allows them to define and plan the information hierarchy of their design for a website, app, or product. This process focuses on how the designer or client wants the user to process information on a site, based on the user research already performed by the UX design team[-1].

## Wireframe examples

For complete beginners, bear in mind the following when deciding on your wireframe creation process[-1]:

- Wireframes drawn with paper and a pencil, or at a whiteboard, have the advantage of looking and being very easy to change, which can help tremendously in early conversations about your website or product.
- With the help of paper-prototypes, you can test with end users at every stage of ideation and design. Changes at these stages are much easier—and therefore cheaper—than changes deemed necessary after coding is under way.
- Switching later to software (after initially hand-drawing your wireframe) allows you to keep track of more detailed decisions.

## Things to consider

Here are a number of ways different designers can structure the process from design to implementation[-1]:

- Wireframe > Interactive Prototype > Visual > Design
- Sketch > Code
- Sketch > Wireframe > Hi-Def Wireframe > Visual > Code
- Sketch > Wireframe > Visual > Code

## So what is HTML

HTML is a markup language that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller, and so on. For example, take the following line of content[-2]:

## Anatomy of an HTML element

The main parts of our element are as follows:

- The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.
- The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.
- The content: This is the content of the element, which in this case, is just text.
- The element: The opening tag, the closing tag, and the content together comprise the element[-2].

## Semantics

In programming, Semantics refers to the meaning of a piece of code — for example "what effect does running that line of JavaScript have?", or "what purpose or role does that HTML element have" (rather than "what does it look like?".)

In HTML, for example, the \<h1> element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."[-3]

Some of the benefits from writing semantic markup are as follows:

- Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
- Screen readers can use it as a signpost to help visually impaired users navigate a page
- Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
- Suggests to the developer the type of data that will be populated
- Semantic naming mirrors proper custom element/component naming

[-1]: https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/
[-2]: https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics
[-3]: https://developer.mozilla.org/en-US/docs/Glossary/Semantics