# pandoc-sidebar-template
This is an html template for pandoc which creates the table of contents in a
sidebar. The sidebar width is coded to 180px but it expands when you mouse
over. Also included is a stylesheet which does a ~~decent~~ ok job at making
everything else look pretty.

Recommended use is:
```
pandoc --toc --css src/pandoc-sidebar-template.css --template pandoc-sidebar-template.html --senf-contained <input document> -o <output document>.html
```