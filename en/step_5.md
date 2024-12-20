## Finishing touches

--- task ---
Select your `index.html` file in the sidebar.

![Sidebar of the code editor showing two files - index.html and style.css](images/recipe-sidebar.png)
--- /task ---

--- task ---
Add a horizontal line at the end of your recipe using the `<hr>` tag.

--- code ---
---
language: html
line_numbers: true
line_number_start: 19
line_highlights: 20
---
</ol>
<hr>
--- /code ---
--- /task ---

--- task --- 
Click **Run** to see the line.

![A banana milkshake recipe in light red text with a grey line underneath it](images/recipe-hr.png)

--- /task ---

The line you’ve just added doesn’t match the style of the rest of your webpage.

--- task ---
Switch back to `style.css` 
--- /task ---

--- task ---
Add some CSS code to set the style of the line. Replace `???` with the colour you chose for your text.

--- code ---
---
language: css
line_numbers: true
line_number_start: 4
---
hr {
    height: 2px;
    border: none;
    background-color: ???;
}
--- /code ---

--- /task ---

--- task ---
Click **Run** to see the new style.

![A recipe for banana milkshake in light red with a light red line underneath it](images/recipe-hr-css.png)
--- /task ---

--- task ---

Add a style to change the bullet points to squares instead of circles:

--- code ---
---
language: css
line_numbers: true
line_number_start: 9
---
ul {
    list-style-type: square;
}
--- /code ---
--- /task ---

--- task ---
Click **Run** to see the new shape.

![A recipe for banana milkshake with bullet points in the shape of squares](images/recipe-ul-css.png)

--- /task ---