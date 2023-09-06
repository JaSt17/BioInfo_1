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
<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Element</th>
      <th>Markdown Syntax</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="/basic-syntax/#headings">Heading</a></td>
      <td><code># H1<br>
          ## H2<br>
          ### H3</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#bold">Bold</a></td>
      <td><code>**bold text**</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#italic">Italic</a></td>
      <td><code>*italicized text*</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#blockquotes-1">Blockquote</a></td>
      <td><code>> blockquote</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#ordered-lists">Ordered List</a></td>
      <td><code>
        1. First item<br>
        2. Second item<br>
        3. Third item<br>
      </code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#unordered-lists">Unordered List</a></td>
      <td>
        <code>
          - First item<br>
          - Second item<br>
          - Third item<br>
        </code>
      </td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#code">Code</a></td>
      <td><code>`code`</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#horizontal-rules">Horizontal Rule</a></td>
      <td><code>---</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#links">Link</a></td>
      <td><code>[title](https://www.example.com)</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#images-1">Image</a></td>
      <td><code>![alt text](image.jpg)</code></td>
    </tr>
  </tbody>
</table>

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Element</th>
      <th>Markdown Syntax</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="/extended-syntax/#tables">Table</a></td>
      <td><code>
          | Syntax      | Description |<br>
          | ----------- | ----------- |<br>
          | Header      | Title       |<br>
          | Paragraph   | Text        |
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#fenced-code-blocks">Fenced Code Block</a></td>
      <td><code>```<br>
      {<br>
      &nbsp;&nbsp;"firstName": "John",<br>
      &nbsp;&nbsp;"lastName": "Smith",<br>
      &nbsp;&nbsp;"age": 25<br>
      }<br>
      ```
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#footnotes">Footnote</a></td>
      <td><code>
        Here's a sentence with a footnote. [^1]<br><br>
        [^1]: This is the footnote.
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#heading-ids">Heading ID</a></td>
      <td><code>### My Great Heading {#custom-id}</code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#definition-lists">Definition List</a></td>
      <td><code>
        term<br>
        : definition
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#strikethrough">Strikethrough</a></td>
      <td><code>~~The world is flat.~~</code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#task-lists">Task List</a></td>
      <td><code>
        - [x] Write the press release<br>
        - [ ] Update the website<br>
        - [ ] Contact the media
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#emoji">Emoji</a><br>(see also <a href="/extended-syntax/#copying-and-pasting-emoji">Copying and Pasting Emoji</a>)</td>
      <td><code>
        That is so funny! :smiley:
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#highlight">Highlight</a></td>
      <td><code>
        I need to highlight these ==very important words==.
      </code></td>
    </tr>
  </tbody>
</table>
