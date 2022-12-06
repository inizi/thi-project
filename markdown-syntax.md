# <a href="https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax">Basic writing and formatting syntax</a>

To use Markdown use the filename extension <code>".md"</code> -- for "markdown" -- such as this file called <code>markdown-syntax.md</code>.

Without the <code>.md</code> the markdown with not be rendered -- but treated a code text.

### Headings:

<pre>
# The largest heading
## The second largest heading
###### The smallest heading
</pre>


# The largest heading
## The second largest heading
###### The smallest heading

---

### Styling text

<pre>
**This is bold text**

*This text is italicized*

~~This was mistaken text~~

**This text is _extremely_ important**

***All this text is important***

<sub>This is a subscript text</sub>

<sup>This is a superscript text</sup>

</pre>

**This is bold text**

*This text is italicized*

~~This was mistaken text~~

**This text is _extremely_ important**

***All this text is important***

<sub>This is a subscript text</sub>

<sup>This is a superscript text</sup>

---

### Quoting text

<pre>
Text that is not a quote

> Text that is a quote
</pre>

Text that is not a quote

> Text that is a quote
---

### Quoting code

Use backticks :

<pre>
Use `git status` to list all new or modified files that haven't yet been committed.
</pre>

Use `git status` to list all new or modified files that haven't yet been committed.

<pre>
Some basic Git commands are:
```
git status
git add
git commit
```
</pre>

Some basic Git commands are:
```
git status
git add
git commit
```
---

### Supported color models

In issues, pull requests, and discussions, you can call out colors within a sentence by using backticks. A supported color model within backticks will display a visualization of the color.

```
The background color should be `#ffffff` for light mode and `#0d1117` for dark mode.
```

The background color should be `#ffffff` for light mode and `#0d1117` for dark mode.

---

### Links

You can create an inline link by wrapping link text in brackets `[ ]`, and then wrapping the URL in parentheses `( )`. 

You can also use the keyboard shortcut `Command+K` to create a link. 

When you have text selected, you can paste a URL from your clipboard to automatically create a link from the selection.

```
This site was built using [GitHub Pages](https://pages.github.com/).
```
This site was built using [GitHub Pages](https://pages.github.com/).


---

### Section links




---

### Relative links

A relative link is a link that is relative to the current file. 

For example, if you have a `README` file in root of your repository, and you have another file in *docs/CONTRIBUTING.md*, the relative link to *CONTRIBUTING.md* in your `README` might look like this:

```
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```


Relative links are easier for users who clone your repository. 

Absolute links may not work in clones of your repository - ***we recommend using relative links to refer to other files within your repository***.


---

### Images


---

### Lists

You can make an unordered list by preceding one or more lines of text with `-`, `*`, or `+`.

```
- George Washington
* John Adams
+ Thomas Jefferson
```
- George Washington
* John Adams
+ Thomas Jefferson


To order your list, precede each line with a number.

```
1. James Madison
2. James Monroe
3. John Quincy Adams
```

1. James Madison
2. James Monroe
3. John Quincy Adams

---

### Nested Lists

---

### Footnotes

<pre>
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
</pre>

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
    
    
---

### Ignoring Markdown formatting


```Let's rename \*our-new-project\* to \*our-old-project\*.```


Let's rename \*our-new-project\* to \*our-old-project\*.

---
---




















