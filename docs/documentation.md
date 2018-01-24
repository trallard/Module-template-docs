# 👓 Documentation

> The following is meant as a more complete set of documentation than the QuickStart guide. If you have not yet completed the QuickStart guide it is recommended that you begin there - as it will provide the necessary steps to setting up your GitHub repository and transferring the source files.

## Software Requirements
In order to edit your Modules  template website locally you will need the following pieces of software:

* Text Editor
* Git
* [Jekyll](https://jekyllrb.com/docs/quickstart/)



## How to use Jekyll to build this site?

### Editing pages online with GitHub

You can edit any page by following the "Edit this page" link in the Quick links nav bar. Alternatively, you can directly navigate to the corresponding .md (Markdown) file in GitHub.

This will drop you in GitHub's file editing interface, where you can modify the source code, preview it, and save your changes, by giving a short description of what you modified. If you have write access to the repository (hint: you do), your modifications will be published right-away. If you do not have right access, you will be asked to fork the repository and make a pull request.

Most of the pages are written in Markdown, which is a textual format for generating formatted text. Markdown syntax is very intuitive, you can get a quick review here or here.

CAVEATS: The Markdown engine used by this site is Kramdown. Its syntax definitions are slightly different form GitHub Flavored Markdown, thus the preview feature in GitHub might not render source as in the final result.

Other reasons why GitHub's preview may not correspond to the final results are:

- Use of Liquid templates in the source. This is seldom used, but some pages use them to access site-wide configuration variables.
- Use of special purpose markup, HTML, and scripts, such as mathematical excerpts written in MathJax.


### Working locally

If you want to do more than the occasional editing, you'll soon
realise GitHub's editor and preview are too limited. It's better to
work locally on your computer.

All you need to work locally is a [Git client](http://git-scm.com/).
[Clone the repository](https://help.github.com/articles/fork-a-repo/#step-2-create-a-local-clone-of-your-fork)
and start coding right away.

At some point, you will need to preview your work, but pushing to
GitHub each time you want to preview is clumsy.  😕
Your best option is to
[install Jekyll and the required dependencies](https://help.github.com/articles/using-jekyll-with-pages/#installing-jekyll)
on your machine. It is recommended to install the
[GitHub pages gem](https://github.com/github/pages-gem) which provides
you with the exact same versions used by GitHub to compile your site. By not doing so you might risk your website not building properly when being pushed to your GitHub repository.

If you already have Ruby, the install part should be as easy as

~~~
gem install github-pages -V
~~~

Note that you will need Ruby headers (`ruby-dev` package on Ubuntu) in
order to compile C dependencies.

On OS X, you can just type `sudo gem install github-pages -V`.

Now you can `cd` into your local clone of the repository and launch
the compilation by

~~~
jekyll serve -w -b
~~~

Your site will be generated in a `_site` sub-directory, and served
live at <http://localhost:4000/> (or <http://username.io/localhost:4000/> depending on your site configuration). Any changes to the sources will
trigger an automatic recompilation!

---

## Important Files and Folders

In order to better understand how everything in your site works, there are a few files and folders that you need to be aware of. These files control the main elements of your site, including your logo, bio photo and navigation. Full documentation of the directory structure can be found [here](https://jekyllrb.com/docs/structure/).

* **\_config.yml** - This is your websites main configuration file. It allows you to set a site title, links to your social media accounts as well as a logo and bio photo image.

* **basic_style.scss** - This file is used to set the colours of your site. The site is set up to accept two colours (primary and secondary). This will set the colours for all the website components. Also, you can change the font and font colour of the banner and navigation bar depending on the colours chosen before.

* **\_posts** - This folder holds all of the posts and presentations for your website. There is one sample post file and one sample presentation file located in this directory by default.

* **images/logo-sheffield.png** - This is the photo that appears on the home page of the website. You can change this to match your institution logo and update the path in your config.yml file.

* **images/dna.png** - This is the default image for the modules cards in your landing page. If you want to use a different one you will have to update the path in your config.yml file.


* **pages/about.md** - This contains the main information of your module and is rendered as the Getting started section in the landing page.
