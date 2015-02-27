# Write documents

The philosophy of Vegetables is to write documents as if it was your notes, i.e. structured logically to make it easy to read.

Clearly : you only have to [write Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)...

## The title

Vegetables is able to guess the document title: the first header is read.

```markdown
# This is my document title

## A subtitle

Some content
```

Here, the document title is `This is my document title`.

If no headers are present, the document file base name is used, for example `my-document` if the Markdown file name is `my-document.md`.

As the template point of view, it is the `title` tag.

## Add metadata

However, it is possible to add document metadata in order to sort documents easily or to display additional informations.

### The reference way

This method is simple: use the Markdown references to add simple data.

For example, to change the default title, simply write, wherever you want:

```markdown
[tag-title]: - (My Web page title)
```

The format is simple: between square brackets: `tag-` followed by the tag name, and between parenthesis: the value.

As this syntax is recognized by Markdown as a reference, it is not displayed when transformed to HTML.

It is possible to define any text metadata with this method, for example the Web site title (`globalTitle`):

```markdown
[tag-globalTitle]: - (The global Web site title)
```

### The Frontmatter way

This is not implemented yet, but it will be quite simple: allow to define more complex tag values using the YAML or JSON syntax as header of the Markdown document:

```markdown
---
title: My Web page title
---
# Welcome!

Some content
```