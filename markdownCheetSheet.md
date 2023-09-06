## BASH & Markdown CheetSheet
# BASH
| Syntax | Description |Common options |
|--------|-------------|----------------|
| ls [option(s)] [file(s)]|List directory contents|-a -l |
|echo [option(s)] [string(s)]|Prints text to the terminal window|-e -n|
|touch [option(s)] file_name(s)|Creates a file|-a, -m, -r, -d|
|mkdir [option(s)] directory_name(s)|Create a directory| -m, -p, -v|
|grep [option(s)] pattern [file(s)]|search|-i, -c, -n|
|man [option(s)] keyword(s)|Print manual or get help for a command| -w, -f, -b|
|pwd [option(s)] |Print working directory|none|
|cd [option(s)] directory|Change directory|none|
|mv [option(s)] argument(s)|Move or rename directory|-i, -b|
|rmdir [option(s)] directory_names|Remove directory|-p|
|cat [option(s)] [file_name(s)] [-] [file_name(s)]|Read a file, create a file, and concatenate files|-n|
|chmod [option(s)] permissions file_name|Sets the file permissions flag on a file or folder|-f, -v|
|history|list your most recent commands| -c, -d|
| cp [option(s)] current_name new_name|copy files and directories|-r, -i, -b|
| kill [signal or option(s)] PID(s)|terminate stalled processes|-p|
|exit |Exit out of a home directory|none|
|locate [option(s)] file_name(s)|Locate a specific file or directory|-q, -n, -i|

# Markdown
## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

'# H1'
'## H2'
'### H3'

### Bold

'**bold text**'

### Italic

*italicized text*

### Blockquote

> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`


## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Highlight

I need to highlight these ==very important words==.

### Subscript

H~2~O

### Superscript

X^2^
