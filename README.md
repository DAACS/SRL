## DAACS Self-Regulated Learning Lab

**THIS REPO IS DEPRACATED. The SRL Lab has moved to Wordpress and is available at https://srl.daacs.net**.

The repository hosts the [Self-Regulated Learning Lab](http://srl.daacs.net) that supports the [Diagnostic Assessment & Achievement of College Skills (DAACS)](http://daacs.net).

**NOTE: This site is currently under development. Please do not copy or use any materials here without prior permission.**

For more information, contact Jason Bryer, Ph.D. at jbryer@excelsior.edu.

### Building the Site

This site is created using the [Jekyll Documentation Theme](http://idratherbewriting.com/documentation-theme-jekyll/) and hosted by [Github Pages](https://pages.github.com/).

To build the site locally run the following command:

```
jekyll build --source docs --destination build
```

Alternatively, you can run a local web server with the following command (available at http://localhost:4000):

```
jekyll server --source docs --destination build
```

### Editing

The source of main content of the website is located in the [https://github.com/ExcelsiorCollege/SRL/tree/master/docs/pages](docs/pages) directory. Content is in Markdown format and converted to HTML either by the Jekyll commands above or when committed to Github. Each page contains metadata (surrounded by `---`) that provides information when the Markdown document is converted to the website format. The following parameters are accepted:

* `title` - The page title.
* `tags` - List of tags for the page (optional).
* `keywords` - List of keywords for the page (optional).
* `summary` - A summary of the page (optional).
* `sidebar` - The name of the navigation sidebar. This should be `mydoc_sidebar` for all of the self-regulated learning pages.
* `permalink` - The name of the HTML file that will be generated. Typically, this is the same name as the Markdown file with a `.html` file extension.
* `folder` - The name of the folder the source file is located. This is used to ensure the `Edit Me` buttons points to the correct source file.
* `toc` - Should a table of contents be created for the page.

#### Markdown

The goal of markdown is to write content that looks reasonable in plain text but can be converted to HTML easily. As such, Markdown is a simple markup langauge. [Click here](Markdown.md) for a list of common Markdown featues.

Since the documents here will be converted to HTML you can use any valid HTML tags as well although discouraged.

___________

The contents of this website were developed under grant #P116F150077 from the U.S. Department of Education. However, those contents do not necessarily represent the policy of the U.S. Department of Education, and you should not assume endorsement by the Federal Government.
