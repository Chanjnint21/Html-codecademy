HTML and Css :
- HTML: Hypertext Markup Language.
- CSS: Cascading Style Sheets
Display text:

- *Paragraphs* (`<p>`) contain a block of plain text.
- `<span>` contains short pieces of text or other HTML. They are used to separate small pieces of content that are on the same line as other content.
- line breaks `<br>`
- `<ul>` to create a list of items in no particular order (unorder list)
- `<ol>` is similar to `<ul>` but this one order list in numbers (order list)
- `<li>` describe an item in a list.

Add Image:

- `<img>` the tag allows you to add an image to a web page. Ex: `<img src="image-location.jpg" />`   *noted : `src` attribute must be set to the image’s *source* or the location of the image
- The `alt` attribute, which means alternative text, brings meaning to the images on our sites. Ex: `<img src="#" alt=" A field of yellow sunflowers" />`
- `<video>` the tag allows you to add a video to a web page. Ex :

`<video src="myVideo.mp4" width="320" height="240" controls>`

`Video not supported`

`</video>`

After the `src` attribute, the `width` and `height` attributes are used to set the size of the video displayed in the browser. The `controls` instruct the browser to include basic video controls such as pausing and playing. If you didn’t use it with not show it as a video but as an image. 

`Video not supported` which will be displayed if the browser is unable to load your video.

Styling text : 

- The `<em>` tag will generally render as [ *italic* ] emphasis.
- The `<strong>` will generally render as **bold** emphasis
