# HTML Boilerplate
Practicing with different Tags
## Head
Is where all the meta information goes, and some requirements for our page to render correctly.
### Meta
Charset encoding so special symbols appear.
### Title
The title of the website's tab.

## Body
Where all the content of the page goes.
### Headings
Displayed larger and bolder than regular text, used for titles.
### Paragraphs
If you write separate paragraphs inside the body element, it will compress them. Separate `<p>` tags will automatically add new lines after.
### Strong
`<strong>` element makes texts <strong>bold.</strong> 

### Using mutiple elements
You can use multiple elements with each other, like so.

```html
<html>
  <head>
  </head>
  <body>
    <p>Lorem ipsum <strong>dolor sit</strong> amet, consectetur adipiscing elit.</p>
  </body>
</html>
```

### em Element
Makes texts <em>italic.</em>

### Nesting
We usually indent elements inside of other elements like in the previous example, this is known as nesting.

### Comments
They are not visible to the browser. They are used to comment on our code so that other developers or our future selves can read them and understand or get context.

### Lists
#### Unordered
Used for things like shopping lists. Usees `<ul>` tag.
#### Ordered
Used for things where order matters, like a top 10 or instructions for something. Uses `<ol>` tag.