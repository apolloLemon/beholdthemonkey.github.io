# beholdthemonkey.github.io


## editing website
- _config.yml stores data (facebook name, site title, etc..)
- all file.md in the main folder will generate a page accessible from the "More" Dropdown
- blog posts are added to _posts, date-name.md

## editing a file.md
Here is a [Markdown CheatSheet](https://www.markdownguide.org/cheat-sheet/) to quickly style text
at the top of file, a section for jekyll to build the .html is needed, for example:
```
---
title: my title
layout: a layout from the _layouts file
---
```
Easiest is to: copy the code from a page with the style you want, and update the relevant fields

## file tree description
main folder <- most pages.md , .git and .gitignore[^1], and md2html stuff
- _includes <- html for parts of pages like navbar
- _layouts <- html for pages
- _posts <- md for blog posts
- _sass <- style code
- assets <- images, behaviour scripts, and styles

[^1]: .git is a folder with different versions of the code, .gitignore is a list of files that aren't uploaded. you might need to add files that your OS puts into the folder.
