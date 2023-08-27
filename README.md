# Animations_assign9

HTML

![Screenshot 2023-08-27 222852](https://github.com/rupesh0511/Animations_assign9/assets/69234169/9821c920-cd63-4357-b8d1-be3215f4b7c5)

'!DOCTYPE html': This declaration specifies that the document is written in HTML5, the latest version of HTML.



'html lang="en"': This is the opening tag for the HTML document. 'lang="en"' indicates that the primary language of the document is English.



'head': This section contains metadata about the document and links to external resources.


'meta charset="UTF-8"': This 'meta' tag sets the character encoding of the document to UTF-8, which supports a wide range of characters and symbols.


'meta name="viewport" content="width=device-width, initial-scale=1.0"': This 'meta' tag defines the viewport settings for responsive web design. It specifies that the width should adjust to the device's width, and the initial zoom level should be set to 1.0.


'title': This 'title' tag sets the title of the web page, which appears in the browser's title bar or tab. In this case, it's set to "Document," but you can replace it with a more descriptive title.


'link rel="stylesheet" href="styles.css"': This 'link' tag links an external CSS stylesheet to the HTML document. The 'href' attribute specifies the path to the stylesheet, which is named "styles.css." This allows you to apply styles defined in the CSS file to your HTML content.


'body': This is the opening tag for the main content of the web page.


'div class="container"': This 'div' element with the class "container" is used as a container to group and structure the content. It's a common practice to use CSS to style elements with specific classes like "container."


'img src="URL" alt="1"': These 'img' tags are used to display images on the web page. The 'src' attribute specifies the source URL of each image, and the 'alt' attribute provides alternative text for each image, describing the content or purpose of the image.


'/div': This is the closing tag for the "container" 'div', marking the end of the content within the container.


'/body': This is the closing tag for the 'body' section, indicating the end of the main content of the web page.


'/html': This is the closing tag for the HTML document, marking the end of the document structure.






CSS

![Screenshot 2023-08-27 222940](https://github.com/rupesh0511/Animations_assign9/assets/69234169/9eaf4389-c56c-4dde-bc83-b255e32861af)

' *': This selector targets all elements on the page.


'margin: 0;', 'padding: 0;', 'box-sizing: border-box;': These properties are applied to all elements, setting margins and padding to zero and specifying the box-sizing as border-box to include padding and borders in element sizes.


'body': Styles applied to the <body> element.


'display: flex;': Makes the body a flex container.


'justify-content: center;': Horizontally centers the content inside the flex container.


'align-items: center;': Vertically centers the content inside the flex container.


'background-color: #000;': Sets the background color of the body to black (#000).


'min-height: 100vh;': Ensures that the body has a minimum height of 100% of the viewport height, making it cover the entire screen.


'.container': Styles applied to elements with the class "container."


'display: flex;': Makes elements with the class "container" flex containers.


'width: 1100px;': Sets the width of the container to 1100 pixels.


'-webkit-box-reflect: below 1px linear-gradient(transparent, transparent, #0004);': Applies a reflective effect below the container with a linear gradient from transparent to transparent to a slightly transparent black (#0004).


'.container img': Styles applied to <img> elements within elements with the class "container."


'max-width: 350px;': Sets a maximum width of 350 pixels for the images.


'transform-origin: center;': Sets the transformation origin to the center of the images.


'transform: perspective(800px) rotateY(20deg);': Applies a 3D perspective transformation, rotating the images by 20 degrees on the Y-axis.


'transition: 0.5s;': Specifies a smooth transition effect with a duration of 0.5 seconds for the images.


'box-shadow: 0px 0px 8px grey;': Adds a shadow effect to the images with a light gray color.


'border-radius: 5px;': Rounds the corners of the images with a 5-pixel radius.


'.container:hover img': Styles applied to images within containers when the container is hovered over.


'opacity: 0.3;': Reduces the opacity of the images to 0.3 (30% visibility) on hover.


'.container img:hover': Styles applied to images within containers when the images are hovered over.


'transform: perspective(800px) rotateY(0deg);': Removes the Y-axis rotation on hover, making the images appear flat.


'opacity: 1;': Sets the opacity of the images to 1 (100% visibility) on hover, making them fully visible.


![Screenshot 2023-08-27 222601](https://github.com/rupesh0511/Animations_assign9/assets/69234169/9eec9292-d8d6-472c-860f-f6886d57d3d3)
