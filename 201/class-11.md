# Reading Notes Class 11

## Explain how the ability to use video and audio on the web has evolved since the early 2000s

User accessibility has grown tremendously. Anyonce can create their own videos and use audio from their phones and is no longer restricted to sitting at a desktop to access the web.

## Describe the use of the src and controls attributes in the <video> element

src is used the same way we use it for the img tag and its to contain a path to the video you want to embed. The controls attribute is to include the browser's own control interface, or build your own interface using JS API.

## Why is it important to have fallback content inside the <video> element?

Some browsers may not support the format that the video is in. So leave a link to a format that is available so that the user can still watch it.

## Write a very short story where <audio> and <video> are characters

## How does Grid layout differ from Flex?

Grid is a two-dimensional grid layout system that adds on to what basic CSS does in styling. Whereas Flex is just a one-dimensional and has many different uses.

## Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences

Container is the direct parent container of all the grid items.

Item would be the the child element that's connected to the container element inside of the grid.

Grid line is the dividing lines that make up the structure of the grid. They can appear vertical or horizontal and reside on either side of a row or column.

## Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

User may be visually impaired and responsive images can be helpful to increase the size of the image and/or let the user know what the image is.

## Define the following <img> attributes srcset and sizes. Write an example of how they are used

srcset defines the set of images we will allow the browser to choose between, and what size each image is. elva- fairy-480w.jpg

sizes defines a set of media conditions and indicates what image size would be best to choose, when certain media conditions are true. (max-width:600px)

## How is srcset more helpful for responsive images than CSS or JavaScript?

You can manually decide how the image fits into the webpage instead of hoping for it to work once you set the size for it.
