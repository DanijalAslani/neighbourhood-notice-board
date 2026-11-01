# PROJECT 01

# Neighbourhood Notice Board

**Difficulty:** Easy  
**Time:** 2 hrs

**The story:** Your street has no place for news. Build ONE web page that works like a wall notice board with 5 notices: a lost cat, a football match, a shop opening, a water cut-off and free tutoring.

## YOU WILL PRACTISE

headings (h1 to h3), paragraphs, lists, links, images with `alt`, `strong`, `em`, `id` anchors.

## YOUR MISSION (ALL MUST BE TICKED)

- [ ] One h1 for the board title and one h2 for each notice (5 notices minimum).
- [ ] At least one ordered list (steps) and one unordered list (items).
- [ ] 2 images, both with meaningful alt text.
- [ ] A table of contents at the top that jumps to each notice using #id links.
- [ ] One external link that opens in a new tab (`target="_blank"`).
- [ ] Zero unclosed tags: check the Elements panel in DevTools (F12).

## GUIDED STEPS

1. Make a folder `notice-board` and a file `index.html`. Open it with Live Server.
2. Type the boilerplate yourself (VS Code shortcut: type `!`) and read every line.
3. On paper, write the 5 notice titles and one important detail for each.
4. Build ONE notice completely. Then repeat the same pattern for the others.
5. Add the table of contents list at the top. Give each notice an h2 and `id`.
6. Hover over elements in DevTools and look at how each tag becomes a box.

## STARTER CODE (TYPE IT, DO NOT PASTE IT)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Street Notice Board</title>
</head>
<body>
    <h1>Our Street Notice Board</h1>
    <ul>
        <li><a href="#lost-cat">Lost cat</a></li>
    </ul>
    <h2 id="lost-cat">Lost cat</h2>
    <p>Last seen near the <strong>blue gate</strong> on Friday.</p>
</body>
</html>
```

## STRETCH CHALLENGES (BONUS)

+ Add a "Back to top" link at the end of every notice.
+ Add an emoji favicon using a `link` tag in the head.
+ Add a 6th notice written in two languages using the `lang` attribute.

## PROVE YOU UNDERSTAND

1. What is the difference between an `id` and a `class`?
2. Why must every image have `alt` text? Name two kinds of people it helps.

**Mentor sign-off:** ____________________  
**Date:** ____________________
