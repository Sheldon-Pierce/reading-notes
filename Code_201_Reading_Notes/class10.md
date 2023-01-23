[Home](../README.md)

## Video and Audio

The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions \<video> and \<audio> elements and the availability of JavaScript APIs for controlling them. We'll not be looking at JavaScript here — just the basic foundations that can be achieved with HTML.

src
In the same way as for the <img> element, the src (source) attribute contains a path to the video you want to embed. It works in exactly the same way.

controls
Users must be able to control video and audio playback (it's especially critical for people who have epilepsy.) You must either use the controls attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API. At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.

The paragraph inside the \<video> tags
This is called fallback content — this will be displayed if the browser accessing the page doesn't support the \<video> element, allowing us to provide a fallback for older browsers.

CSS Grid Layout (aka “Grid” or “CSS Grid”), is a two-dimensional grid-based layout system that, compared to any web layout system of the past, completely changes the way we design user interfaces. CSS has always been used to layout our web pages, but it’s never done a very good job of it. First, we used tables, then floats, positioning and inline-block, but all of these methods were essentially hacks and left out a lot of important functionality (vertical centering, for instance). Flexbox is also a very great layout tool, but its one-directional flow has different use cases — and they actually work together quite well! Grid is the very first CSS module created specifically to solve the layout problems we’ve all been hacking our way around for as long as we’ve been making websites.

Grid Container
The element on which display: grid is applied. It’s the direct parent of all the grid items. In this example container is the grid container.

Grid Item
The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.

Grid Line
The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.

## Responsive Images

Responsive image technologies were implemented recently to solve the problems indicated above by letting you offer the browser several image files, either all showing the same thing but containing different numbers of pixels (resolution switching), or different images suitable for different space allocations (art direction).

So, what is the problem that we want to solve with resolution switching? We want to display identical image content, just larger or smaller depending on the device — this is the situation we have with the second content image in our example. The standard <img> element traditionally only lets you point the browser to a single source file

srcset defines the set of images we will allow the browser to choose between, and what size each image is. Each set of image information is separated from the previous one by a comma. For each one, we write:

1. An image filename (elva-fairy-480w.jpg)
3. 2. A space
The image's intrinsic width in pixels (480w) — note that this uses the w unit, not px as you might expect. An image's intrinsic size is its real size, which can be found by inspecting the image file on your computer (for example, on a Mac you can select the image in Finder and press Cmd + I to bring up the info screen).

sizes defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true — these are the hints we talked about earlier. In this case, before each comma we write:

A media condition ((max-width:600px)) — you'll learn more about these in the CSS topic, but for now let's just say that a media condition describes a possible state that the screen can be in. In this case, we are saying "when the viewport width is 600 pixels or less".
A space
The width of the slot the image will fill when the media condition is true (480px)


