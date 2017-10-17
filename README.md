# man-book
Tool to easily author "books" that include manpages, for example to prepare for LPIC exams

The idea is to author a book with Markdown, using `pandoc` to produce a beautiful PDF document (via LaTeX).
manpages can be included through a templating syntax, they are converted to PDF on-the-fly (and then cached)
before being included in the resulting document.

The tool is intended to work out-of-the-box, but I plan to support more flexibility to customize the used
LaTeX code for better control of the appearance.

**Requirements:**

* Python3
* LaTeX (e.g. TeXLive, no fancy package requirements)
* pandoc
* all programs whose manpages are intended to be used
