---
title: Ultimate Markdown Demo
author: Example Author
tags: [markdown, demo, cheatsheet]
date: 2026-04-19
---

# Ultimate Markdown Demo

Welcome to a **complete Markdown example** showing many common and advanced features.

---

## Headings

# Heading 1
## Heading 2
### Heading 3
#### Heading 4

---

## Text Formatting

**Bold text**

*Italic text*

***Bold + Italic***

~~Strikethrough~~

Inline code: `print("Hello Markdown")`

Escaped characters: \*not italic\*

---

## Paragraphs and Line Breaks

This is the first paragraph.

This is another paragraph with  
a manual line break.

---

## Lists

### Unordered List

- Item 1
- Item 2
  - Nested Item
  - Another Nested Item
- Item 3

### Ordered List

1. First
2. Second
3. Third

---

## Task Lists

- [x] Write Markdown demo
- [x] Add examples
- [ ] Publish documentation

---

## Links

[OpenAI](https://openai.com)

Link to section: [Go to Tables](#tables)

---

## Images

![Example Image](https://via.placeholder.com/300)

Clickable image:

[![Thumbnail](https://via.placeholder.com/150)](https://via.placeholder.com/600)

Centered image using HTML:

<p align="center">
  <img src="https://via.placeholder.com/200" width="200"/>
</p>

---

## Blockquotes

> This is a quote.
>
> > Nested quote inside another quote.

---

## Tables

| Name | Age | Role |
|-----|-----|------|
| Alice | 30 | Developer |
| Bob | 40 | Manager |
| Clara | 28 | Designer |

### Table Alignment

| Left | Center | Right |
|:----|:------:|-----:|
| A | B | C |
| 1 | 2 | 3 |

---

## Definition List

**HTTP**
: HyperText Transfer Protocol

**API**
: Application Programming Interface

---

## Horizontal Rule

---

## Code Blocks

### Python Example
```python
def greet(name):
print(f"Hello {name}")

greet("World")
```

{
  "name": "Markdown Demo",
  "version": "1.0",
  "features": ["tables", "lists", "code"]
}

Inline HTML
This is <strong>bold using HTML</strong> and <em>italic using HTML</em>.

<p style="color:red;">This text is styled with HTML.</p>

:rocket: :fire: :tada: :smile:

Here is a statement with a reference.[^1]

Another reference here.[^2]

[^1]: This is the first footnote.

[^2]: This is the second footnote.
$$

E = mc^2

$$

graph TD
A[Start] --> B{Decision}
B -->|Yes| C[Continue]
B -->|No| D[Stop]
C --> E[Finish]
D --> E
