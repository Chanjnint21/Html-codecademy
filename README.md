HTML and Css :
- HTML: Hypertext Markup Language.
- CSS: Cascading Style Sheets

Declare : 

- `<!DOCTYPE html>` to let web browser know you are using HTML 
- `<head></head>` is a tag that is always above the body element and is a part of this HTML metaphor…the metadata in the head is information about the page itself.
- `<body></body>` is a tag that contain the content the information and the contain in page

Tag :

- Some elements need the open and close tag and some only need an open tag. Example: `<body></body>` need open and close, `<br>` doesn't need close tag.

Display text:

- `<title></title>` is a tag that use to display on web browser Tab [ Noted: It is always in the head ]
- *Paragraphs* (`<p>`) contain a block of plain text.
- `<span>` contains short pieces of text or other HTML. They are used to separate small pieces of content that are on the same line as other content.
- line breaks `<br>`
- `<ul>` to create a list of items in no particular order (unorder list)
- `<ol>` is similar to `<ul>` but this one order list in numbers (order list)
- `<li>` describe an item in a list.

Add link, Image, & video :

- `<img/>` the tag allows you to add an image to a web page. Ex: `<img src="image-location.jpg" />`   *noted : `src` attribute must be set to the image’s *source* or the location of the image
- The `alt` attribute, which means alternative text, brings meaning to the images on our sites. Ex: `<img src="#" alt=" A field of yellow sunflowers" />`
- `<video></video>` the tag allows you to add a video to a web page. Ex :
    
    `<video src="myVideo.mp4" width="320" height="240" controls>`
    
    `Video not supported`
    
    `</video>`
    
    After the `src` attribute, the `width` and `height` attributes are used to set the size of the video displayed in the browser. The `controls` instruct the browser to include basic video controls such as pausing and playing. If you didn’t use it with not show it as a video but as an image. `Video not supported` which will be displayed if the browser is unable to load your video.
    
- external link ( link to different page ): `<a></a>` Anchor element is a tag that can add a link to a web browser, but it requires `href` in it, or otherwise, it is useless. Example: `<a href="insert link here">This Is A Link To Wikipedia</a>` …… `target` attribute specifies how a link should open. For example, when you use target=”_blank” so when a link clicks it will open an external web page in a new window/tab. `<a href="link" target="_blank">The Brown Bear</a>`
- Internal link: You can link to your other webpage in your folder…For example: in your project, you have two folders: `About_bear.html`, `Aboutme.html` so to link from your first page About_bear.html to Aboutme.html You need to put `<a href="./Aboutme.html">About Me</a>` by [ ./ ] use to tell the browser to change the directory of the file in your project folder.
- put the link in the image to be more productive: `<a href="[https://en.wikipedia.org/wiki/Brown_bear](https://en.wikipedia.org/wiki/Brown_bear)" target="_blank"><img src="[https://content.codecademy.com/courses/web-101/web101-image_brownbear.jpg](https://content.codecademy.com/courses/web-101/web101-image_brownbear.jpg)" /></a>`
- Linking to the same page :

Styling text : 

- The `<em>` tag will generally render as [ *italic* ] emphasis.
- The `<strong>` will generally render as **bold** emphasis
