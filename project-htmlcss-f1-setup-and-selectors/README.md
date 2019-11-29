# Project CSS F1 Setup and Selectors

Topics: Inline Styles
, The <style> Tag
, Linking the CSS File
, Tag Name
, Class Name
, Multiple Classes
, ID Name
, Classes and IDs
, Specificity
, Chaining Selectors
, Nested Elements
, Chaining and Specificity
, Important
, Multiple Selectors

## Project Title : Letter Format

1. Create a folder with your name like `john` inside this folder.
2. In this newly created folder, create an html file named `letter-format.html`
3. Add current code to that file:

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      /* css code here */
    </style>
  </head>
  <body></body>
</html>
```

4. Create a paragraph with this text under body tag. Then use inline style to set text color bule and font size 18px.

```
Letter Date
2019/09/10
```

Open `letter-format.html` in the browser and monitor changes.

5. Create another paragraph with this text after previous paragraph. Use internal style to define a style for p tag and set the color to green.

```
Contact Information
Your Name
Your Email Address
```

6. At the same location as html file, create a css file named `style.css`

7. Link `style.css` to `format-letter.html`. Hint: Add `style` tag to head section of html file and set href, ref and type attributes.

8. Set `font-weight` to `bold` for `p` tag in the `style.css` and check changes in the browser.

9. Add a `div` tag after prvious `p` tag with this text. set `div`s color brown in the `style.css`.

```
Greeting
Dear Mr./Ms. Last Name:
```

10. Add another `div` with this text and set its `class` to `main`. Set `main` class font to italic in `the style.css`.

```
Body of Letter
The first paragraph of your letter should provide an introduction as to why you are writing so that your purpose is obvious from the very beginning.
```

11. Add another `div` with this text and set its `id` to `closing`. Set `closing` id font decoration to underline.

```
Closing
Best regards,
Your Name
```

12. Create a new `div` with `class="list"`. Then, add an unordered list include these items.

```
Letter Date
Contact Information
Greeting
Body of Letter
Closing
```

13. Change items colors to red through Chaining and Specificity. All `li`s inside `list` class should be green.

## Want to get reviewed?

Send Pull Request. Check how to deliver your code: https://codingwithbasir.com/how-to-deliver-projects/

## Need help?

Download Free eBook https://codingwithbasir.com/download
