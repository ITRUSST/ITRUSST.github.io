# ITRUSST
**International Transcranial Ultrasonic Stimulation Safety and Standards**  

*copyright: ITRUSST
version: 2021-02-18*

# ITRUSST documentation

This repository contains the ITRUSST documentation hosted on <https://itrusst.github.io>.

## Technical notes

- The website is rebuilt after every pushed commit; this can take up to 5 minutes.
- File names should not contain spaces or other special characters.
- Pages that contain tags must have a title.
- Tags should be in lower case.
- All tags should appear on a single line.
- Variables passed in an include must be specified in quotes.
- Code blocks should have an empty line before and after them.
- Shared pages should go in \_include/shared.
- Markdown documentation can be found on <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>.
- Liquid documentation can be found on <https://help.shopify.com/en/themes/liquid> and <https://shopify.github.io/liquid>.
- Jekyll cheatsheet can be found on <https://devhints.io/jekyll>.

## Limitations when viewing on GitHub

Most of the Markdown formatting will show up nicely on GitHub, but there are some limitations.

- Hyperlinks will not be pointing to the correct pages.
- Images are not included correctly.
- YouTube videos will not be included correctly.
- Highlighted sections will not show correctly.
- Code blocks don't have syntax highlighting.

## Evaluating the website locally

If you make changes that you want to evaluate prior to publishing them, you have to install Ruby, Bundler, Jekyll, etc. Subsequently you can do

    bundle exec jekyll serve --incremental --livereload

which will convert the Markdown into HTML and serve the complete website on <http://localhost:4000>.

## Checking for broken links and missing images

    wget --spider -r -nd -nv -o spider.log http://localhost:4000
    grep -B1 'broken link!' spider.log  | grep http > broken.log
