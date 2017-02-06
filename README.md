afaq
====

This repository contains the source files from the online book [An Anarchist FAQ (AFAQ)](http://www.anarchism.pageabode.com/afaq/index.html) obtained automatically with [afaq_scraper](https://0xacab/ju/afaq-scraper), which download the HTML files and convert them to TXT files.
The book is available in Debian as the *anarquism* package.
Currently, every time there is a new version of the book, the Debian maintainers need to manually run an script to download the HTML files and convert them to TXT, but there is no upstream code to perform that process nor upstream of the source files to easily compare new versions.
From the point of view of developers, mantainers, it would be great if there would be an upstrem repository of the sources, to automatically detect changes in the content of the book and generate a new package.
It would be also beneficial for the contributors to the content or translations to be able to detect changes and/or directly modify the sources.
This repository could be an upstream reference for the Debian package while the authors of the book do not have their own public repository.
One potential issue for the authors to have a public repository is that git commits show the author name and email. The author name and email could be however a shared account between different authors.
HTML and TXT files are not suitable formats for authors/translator to edit the contents. More suitable formats are [Markdown](https://daringfireball.net/projects/markdown/) or [reStructuredText](http://docutils.sourceforge.net/rst.html) that can be converted to PDF, E-book or other formats. For this reason the `afaq_scraper` generates also Markdown files that are included in this repository.


License
--------
GPLv2

Copyright
----------
1995-2017 The Anarchist FAQ Editorial Collective <anarchistfaq at yahoo dot co dot uk>
