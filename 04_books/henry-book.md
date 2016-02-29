---
title: "Henry's Classics Book Theme"
---

Another Jekyll static site generator theme for classic books
(e.g. Strange Case of Dr. Jekyll and Mr Hyde, A Tale of Two Cities, The Trial, etc.)
that is, a ready-to-fork template pack.

For example:

```
├── _config.yml                               # book configuration
├── _chapters                                 # sample chapters
|   ├── 01.md
|   ├── 02.md
|   ├── ...
|   └── 10.md
├── _layouts                           
|   └── default.html                   # master layout template
├── css                               
|   ├── _settings.scss                 # style settings (e.g. variables)
|   └── style.scss                     # master style page
└── index.html                         # all-in-one page book template
```

will result in an all-in-one book page:

```
└── _site                                # output build folder; site gets generated here
    ├── css
    |   └── style.css                    # styles for pages (copied 1:1 as is)
    └── index.html                       # all-in-one book page
```

## How-to Build Your Own Book

### Step 1: Add your chapters to the `_chapters/` folder

Replace all text files in the `_chapters` folder with your own.


### Step 2: Add the book title and author in the `_config.yml` file

Next change the book title and author in the `_config.yml` file:

```
title:  Strange Case of Dr. Jekyll and Mr. Hyde
author:
  name: Robert Louis Stevenson
```

with your own book title and author name. That's it. Happy reading.

### Live Demo

See a live demo @ [`henrythemes.github.io/jekyll-book-theme` »](http://henrythemes.github.io/jekyll-book-theme)

