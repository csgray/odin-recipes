# odin-recipes

A collection of recipes as part of The Odin Project. This project implements basic HTML structure and elements such as headers, paragraphs, images, lists, and links.

## HTML

### Template

All of the HTML pages started with the same template:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Title</title>
  </head>
  <body>
    <h1>Title</h1>
    <img src="../images/recipe.jpg" alt="A picture of the food" />

    <h2>Description</h2>
    <p>Write something nice about the recipe.</p>

    <h2>Ingredients</h2>
    <ul></ul>

    <h2>Steps</h2>
    <ol></ol>
  </body>
</html>
```

The template is basic HTML boilerplate plus a few headers, an image, and lists.

### Images

Pages perform better when images are provided and rendered at the right size. To get that size, install ImageMagick and use:

```
convert -resize XX% source.jpg dest.jpg
```
