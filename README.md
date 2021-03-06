Table of Content Plugin for Mecha CMS
=====================================

> Automatic table of content generator.

### Introduction

This plugin will automatically create table of content on the page that has several headlines which you can use as a quick jump links. If you omit the check sign in the _Insert Table of Content_ option, then the table of content will not be inserted at the top of the article content, and this plugin will only serve as an automatic permalink ID creator on each headline in your article.

#### Determine Your Own ID

You always have the control to determine your own headline ID using the **Markdown Extra** syntax. This plugin will not overwrite the specific ID that you specify in the headline:

~~~ .markdown
### Headline Special 1 {#special-1}
~~~

#### Exclude Headline from TOC

Add a `not-toc-stage` class to the headline to exclude it from TOC list:

~~~ .markdown
### Example Header 3 {.not-toc-stage}
~~~

#### Custom TOC Placement

Add a `{{toc}}` _shortcode_ anywhere in the page content to mark the position you want to put the generated TOC tree to.