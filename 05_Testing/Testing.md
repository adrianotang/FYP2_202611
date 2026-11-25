# Heading 1 (Main Document Title)

Welcome to this sample Markdown file. Paragraphs are separated by a single blank line. 
To create a line break within the same paragraph, end a line with two spaces or use `<br>`.

---

## Heading 2 (Major Section)

### Heading 3 (Subsection)

#### Heading 4

##### Heading 5

###### Heading 6

---

## Text Emphasis & Styling

* **Bold text** using `**double asterisks**` or `__double underscores__`
* *Italic text* using `*single asterisks*` or `_single underscores_`
* ***Bold and italic*** using `***triple asterisks***`
* ~~Strikethrough~~ using `~~double tildes~~`
* `Inline code` using `` `single backticks` ``
* H~2~O (Subscript) and X^2^ (Superscript) — *supported in select Markdown flavors*

---

## Blockquotes

> This is a standard blockquote. It is useful for callouts or quoting external sources.
>
> > You can also nest blockquotes by adding a second `>` symbol.

---

## Lists

### Unordered List
* First item (using `*`, `-`, or `+`)
* Second item
  * Nested item (indent with 2 or 4 spaces)
  * Another nested item
* Third item

### Ordered List
1. First step
2. Second step
   1. Sub-step A
   2. Sub-step B
3. Third step

### Task List (Checkboxes)
- [x] Completed task
- [ ] Incomplete task
- [ ] Pending review

---

## Links & Images

### Links
* **Standard Link:** [Markdown Guide](https://www.markdownguide.org "Optional Hover Title")
* **Automatic Link:** <https://github.com>
* **Section Anchor Link:** [Jump to Tables](#tables)

### Images
Standard image syntax mirrors link syntax, prefixed with an exclamation mark (`!`):

![Alt text describing the image](https://placeholder.com "Optional Image Title")

* **Local image example:** `![Project Logo](./assets/logo.png)`
* **Clickable image (Image inside a link):**
  [![Clickable Badge](https://shields.io)](https://www.markdownguide.org)

---

## Tables

Use pipes (`|`) to separate columns and hyphens (`---`) to define the header row. Use colons (`:`) to align text.

| Left-Aligned | Center-Aligned | Right-Aligned |
| :--- | :---: | ---: |
| Row 1, Col 1 | Centered Text | \$100.00 |
| Row 2, Col 1 | `Inline Code` | \$25.50 |
| Row 3, Col 1 | **Bold Cell** | \$1,400.00 |

---

## Code Blocks

Wrap multi-line code in triple backticks (` ``` `) and specify the programming language for syntax highlighting:

```python
def greet(name: str) -> str:
    """Return a formatted greeting."""
    return f"Hello, {name}!"

print(greet("Markdown"))
```

```json
{
  "file": "sample.md",
  "version": 1.0,
  "active": true
}
```

---

## Footnotes & Escaping

Here is a sentence with a footnote reference[^1].

To display literal Markdown characters without triggering formatting, place a backslash (`\`) before them: \*not italic\*, \# not a heading.

[^1]: This is the footnote definition at the bottom of the document.
