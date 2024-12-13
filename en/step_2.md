## Ingredients

The example recipe you’ll see in this project is for a banana milkshake, but you can choose your own.

Let’s list the ingredients that are needed for your recipe.

--- task ---
Open the [starter project](https://staging-editor.raspberrypi.org/en/projects/recipe-starter){:target="_blank"}.
--- /task ---

--- task ---
In the `<body>` section, add a title for your recipe.

--- code ---
---
language: html
line_numbers: true
line_number_start: 7
line_highlights: 8-10
---
<body>
<h1>Banana Milkshake</h1>

<h3>Ingredients:</h3>

</body>
--- /code ---

--- /task ---

--- task ---
The `<ul>` tag creates an unordered list. Add the tags to start and end your list. 

--- code ---
---
language: html
line_numbers: true
line_number_start: 10
line_highlights: 11-13
---
<h3>Ingredients:</h3>
<ul>

</ul>

</body>
--- /code ---

--- /task ---

+ View your webpage, and you should see your two headings.

![screenshot](images/recipe-headings.png)

You won’t see your list yet though, because you haven’t added any list items to it!

+ The next step is to add list items into your list, by using the `<li>` tag. Add the following code inside your `<ul>` tag:

```
<li>1 banana</li>
```

![screenshot](images/recipe-ul.png)

As your list is unordered, there are no numbers next to the list items, just bullet points.

