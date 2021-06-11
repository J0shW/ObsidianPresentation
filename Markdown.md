# 6. Markdown

All the standard markdown syntax is available.

[Markdown Syntax](obsidian://open?vault=Obsidian%20Help&file=How%20to%2FFormat%20your%20notes)

But there are some unique things Obsidian can do.

## Checkboxes
- [x] Prep for Obsidian demo
- [ ] Give presentation at developer meeting

## Tables
You can create tables by assembling a list of words and dividing them with hyphens `-` (for the first row), and then separating each column with a pipe `|`:

First Header | Second Header
------------ | ------------
Cell 1 | Cell 2
First column | Second column

## Highlighting
Use two equal signs to ==highlight text==.

## Footnotes
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

## Comments
Use `%%` to enclose comments, which will be parsed as Markdown, but will not show up in the preview.
%%This cannot be seen in preview%%

> Now let's make things pretty! [[Customization]]

[^1]: meaningful!
[^bignote]: Here's one with multiple paragraphs and code.
	Indent paragraphs to include them in the footnote.
