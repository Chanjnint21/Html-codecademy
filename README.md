Bear.html UI project:
<a href = "https://www.figma.com/proto/V7QILZX6V9nxEoCOaykXx0/BEAR?node-id=14%3A94&starting-point-node-id=14%3A94&scaling=contain" target="blank_">https://www.figma.com/proto/V7QILZX6V9nxEoCOaykXx0/BEAR?node-id=14%3A94&starting-point-node-id=14%3A94&scaling=contain</a>
<br>
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

Table :

`<table> </table>` is the element will contain all of the tabular data we plan on displaying.

- `<thead>`defines the headings of table columns
- `<body>` is a semantic element that will contain all table data other than table heading and table footer content
- use `<tr></tr>` Table Row to create a rows of table then >
- use `<th></th>` Table Heading to add titles to rows and columns of a table
- use `<td></td>` Table Data to insert the data in `<tr></tr>`
- `scope` attribute specifies whether a header cell is a header for a column, row, or group of columns or rows
1. `row` - this value makes it clear that the heading is for a row.
2. `col` - this value makes it clear that the heading is for a column.

Example : `<th scope ="col">Company Name</th>`

- In the older version of HTML, we can use the border to create a border of the table

`<table border="1">`

`<tr></tr>`

`</table>`

but now we can use CSS effect instead.

- `colspan` attribute on a table header `<th>`or table data `<td>`  element indicates how many columns that particular cell should span within the table. It’s like you try to merge the current volume and the right volume into one. Can set value from 1 - 1000. Example: `<td colspan="2">col 1 (will span 2 columns)</td>`
- `rowspan` attribute is used for data that spans multiple rows. It’s like you try to merge the current volume and the below volume into one
- `<tfoot>` uses table rows to give footer content or to summarize content at the end of a table

Form: 

- The purpose of a `<form>` is to allow users to input information and send it.
- The `<form>`‘s `action` attribute determines where the form’s information goes.
- The `<form>`‘s `method` attribute determines how the information is sent and processed.
- To add fields for users to input information we use the `<input>` element and set the `type` attribute to a field of our choosing:
    - Setting `type` to `"text"` creates a single row field for text input.
    - Setting `type` to `"password"` creates a single row field that censors text input.
    - Setting `type` to `"number"` creates a single row field for number input.
    - Setting `type` to `"range"` creates a slider to select from a range of numbers.
    - Setting `type` to `"checkbox"` creates a single checkbox which can be paired with other checkboxes.
    - Setting `type` to `"radio"` creates a radio button that can be paired with other radio buttons.
    - Setting `type` to `"list"` will pair the `<input>` with a `<datalist>` element if the `id` of both are the same.
    - Setting `type` to `"submit"` creates a submit button.
- A `<select>` element is populated with `<option>` elements and renders a dropdown list selection.
- A `<datalist>` element is populated with `<option>` elements and works with an `<input>` to search through choices.
- A `<textarea>` element is a text input field that has a customizable area.
- When a `<form>` is submitted, the `name` of the fields that accept input and the `value` of those fields are sent as `name=value` pairs.
