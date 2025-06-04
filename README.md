Quick guide
===========

To add a new post, follow these steps: 

1. WARNING DO NOT SKIP: `git pull`, to make sure you are up to date (managing
   conflicts between files compiled by quarto is not fun).

2. create new sub-directory `DD-MM-YYYY-name` in directory `posts/`.

3. Write your post inside this sub-folder as a qmd file, with the appropriate preamble,
  see [here](https://quarto.org/docs/websites/website-blog.html#posts-directory).

4. go back to root folder (important), compile: `quarto render .`, 

5. check you are happy with the locally compiled version, using your browser, e.g. `firefox docs/index.html`

6.  `git add .`  (so that you don't forget any file, in particular the ones
    generated automatically by quarto)

7. `git commit` and `git push`

Under the hood
==============

Quarto is configured to render the blog in the docs folder, as recommended here:
<https://quarto.org/docs/publishing/github-pages.html#render-to-docs>

The github repo is configured accordingly.
