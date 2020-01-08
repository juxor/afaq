afaq
====


This repository contains the source files from the online book
[An Anarchist FAQ (AFAQ)](http://www.anarchism.pageabode.com/afaq/index.html)
obtained automatically with [afaq-dl](https://0xacab.org/ju/afaq-dl),
which download the HTML files and convert them to other formats.


The book HTML files and other format files are available in Debian
as the [anarchism](https://packages.debian.org/jessie/anarchism) package.
Until the package version 14.0, every time there was a new version
of the book, the Debian maintainers needed to manually run an script
(not included in any repository, not the package)
to download the HTML files.
Then the package had to be rebuilded to generate the TXT files.
The code to generate the TXT files was only include in the package sources,
and there was not `upstream` code to perform the process nor `upstream`
source files which which versions could be easily compared.


This repository is intended to be modified automatilly by `afaq-dl`.
If `afaq-dl` code,the HTML pages from the AFAQ Website or a proxy
changes the content, it will be saved in this repository and
the differences can be compared thanks to the git history.
A human checks the last commit and can generate a new release.


This repository could be an upstream reference for the Debian package
while the authors of the book do not have their own public repository.

One potential issue for the authors to have a public repository
is that git commits show the author name and email.
The author name and email could be however a shared account between
different authors.


HTML and TXT files are not suitable formats for authors/translator
to edit the contents.
More suitable formats are [Markdown]
(https://daringfireball.net/projects/markdown/)
or [reStructuredText](http://docutils.sourceforge.net/rst.html)
that can be later converted to PDF, E-book or other formats. 
For this reason the `afaq-dl` generates Markdown files that are included
in this repository.


This repository should also be beneficial for the contributors
to the content or translations as it is easier to check changes
and/or directly modify the sources.


**NOTE**:

Readers using the Debian package, they can still report content bugs
to the `anarchism` package.
Either the Debian package or this repository would be modified.


Other readers not using this Debian package can report content bugs
as usual in Git repositories, creating an issue in the
[issue tracker](https://0xacab.org/ju/afaq/issues)
or a [pull request](https://0xacab.org/ju/afaq/merge_requests).
     
Probably the best directory to modify the content in pull requests
is the `markdown` one, as the differences would be easier to see.

To modify the HTML structure in pull requests use instead the `html` one.

License
--------
GPLv2

Copyright
----------
1995-2017 The Anarchist FAQ Editorial Collective <anarchistfaq at yahoo dot co dot uk>

