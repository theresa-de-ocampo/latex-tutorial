# Learning LaTeX

Based on [LaTeX - Full Tutorial for Beginners](https://www.youtube.com/watch?v=ydOTMQC7np0)

## VS Code Set-up

1. Install LaTeX Workshop extension at VS Code
2. Install a LaTex Distribution: MikTeX
3. Install Strawberry Perl
4. Open MikTeX console, and check for any errors. Just hit update in case of errors.

## Notes

- Soft Return - `\\`, not indented
- Hard Return - blank line, indented since it inserts as a new paragraph
- Math Mode - `$insert your math equation$`. Same with markdown.
- Caret sign only works in Math mode.
- If you want to keep something on a single line, surround it with curly brackets.
- Display Math Mode - double dollar signs
- Inline Math Mode - single dollar signs
- If you do `\centering`, then everything that comes after that will be centered.
- If you do `\large`, then everything that comes after that will be large.
- You can manually put in the date `\date{December 1, 2023}`
- If you don't want your sections to be numbered, add asterisk: `\section*{Linear Functions}`
- `\usepackage{fullpage}` will give 1 inch margin on all sides.
- You can also modify the document setting like so: `\usepackage[top=1in, bottom=1in, left=0.5in, right=0.5in, paperwidth=8.5in, paperheight=11in]{geometry}`.
- American Mathematical Society (AMS)
- Blackboard-bold is a style of writing bold symbols on a blackboard by doubling certain strokes, commonly used in mathematical lectures.
- If you don't specify options at import, then you can import multiple packages in one line: `\usepackage{amsfonts, amssymb, amsmath}`.
- Macros are used to define your own LaTeX commands.
- `\textstyle` applies the style used for Mathematics typeset in paragraphs.
- `\displaystyle` applies the style used for Mathematics typeset on lines by themselves. That's why display style is a little bigger than text style.
- `\scriptstyle` applies the style used for subscripts or superscripts.
- `\clearpage` command ends the current page.
- `.cls` and `.sty` files are supplementary files that increase the functionality of LaTeX. They are the files loaded with the `\documentclass{...}` and `usepackage{...}` commands, respectively. We generally call `.cls` files _classes_, and `.sty` files 'style files' or often just _packages_.
- The `\LoadClass{extarticle}` command is used in LaTex to load a document class. The `extarticle` class is an extension of the standard LaTeX `article` class. The `extsizes` package provides additional font size options beyond what the standard document classes (`article`, `report`, `book`) offer. It supports `8pt`, `9pt`, `10pt`, `12pt`, etc.
