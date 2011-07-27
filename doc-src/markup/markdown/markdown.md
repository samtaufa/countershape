Use a page filename with the file extension ".mdtext", ".md" or from the configuration
index.py use:

<pre>
import countershape
from countershape import markup
this.markup = markup.Markdown()
</pre>

to render all pages using this markdown2.

Options for the markdown2 command-line utility can be included such as:

`this.markup = markup.Markdown( extras=["code-friendly"] )`

Note: **Spaces** are significant when including paramater options.

Refer to the [python-markdown2](https://github.com/trentm/python-markdown2) project
site for installation, and more complete documentation.

[Markdown](http://daringfireball.net/projects/markdown/) is a text-to-HTML 
conversion tool for web writers. Markdown allows you to write using an 
easy-to-read, easy-to-write plain text format, then convert it to structurally 
valid XHTML (or HTML). 

Thus, "Markdown" is two things: (1) a plain text formatting syntax;
and (2) a software tool, that converts the plain text
formatting to HTML.