# Simple LaTeX template for resumes and CVs

A LaTeX template for resumes and CVs.
The only special thing it has is that it's small and uses readily-available packages.

To compile, you *must* use XeLaTeX.
You should have it already if you installed TeXLive.
To change fonts, take a look at the [fontspec manual](http://ctan.math.utah.edu/ctan/tex-archive/macros/latex/contrib/fontspec/fontspec.pdf) and also at your installed OTF typefaces.

Feel free to modify the template as much as you need,
I tried to make it as simple and straightforward as possible.

If you want to look at examples, here is one:

![Resume example](/examples/resume.png)

Its corresponding source code is located in the `examples` folder.

Beware that many blank spaces are fine-tuned to 12pt and you'll have to change them accordingly if you change the font size.
Also, this template doesn't implement any special way of working with bibliographies,
so you'll have to use the built-in bibliography engines or the `\closerlist` command from the template.
