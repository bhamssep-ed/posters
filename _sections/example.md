---
layout: default
title: Example
hidden: true
---

<!-- Comments are written like this -->
<!-- The above section is some meta data for the file used when generating
the HTML -->

## Headings

Headings are preceded with a multiple of `#` for the level of subheading. For
example,

```markdown
# Title
## Section
### Subsection
```

renders like this,

# Title
## Section
### Subsection

## Code

Above, we have used a codeblock, surrounded by triple start-quotes \`\`\`
and the name of the programming language for syntax highlighting.

Inline code may be surrounded by single start-quotes.

## Lists

Unordered list items are preceded by either an asterisk, `*` or a hyphen, `-`.
E.g.

```markdown
* Item 1
- Item 2
    - Sub-item 1
    * Sub-item 2
```

renders like this,

* Item 1
- Item 2
    - Sub-item 1
    * Sub-item 2

Ordered lists are preceded by their number and a full-stop, e.g.

```markdown
1. Item 1
2. Item 2
```

renders like this,

1. Item 1
2. Item 2

## Links and Images

Links are written like `[this](<url goes here>)`, which renders like
[this]().

Images are written like this, `![alt text](../img/people/Basri_Tile.png)` which
renders like this,

![alt text](../img/people/Basri_Tile.png)
