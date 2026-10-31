# PDF store B

PDF bytes for the [Pro InstControl library](https://pro-instcontrol.github.io/books/),
published through GitHub Pages so the reader can stream them with range requests
from the same origin as the site.

Names are content-addressed (`name__sha1-16.pdf`) and never change. Books over
90 MB are split into page-range parts (`__pNofM.pdf`), because GitHub refuses a
single file above 100 MB.
