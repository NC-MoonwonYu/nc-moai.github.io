# Motion AI Team Website

This is a website for Motion AI Team, Game AI Lab, NCSOFT based on Github Pages and Jekyll.

## Table of Contents
1. [Table of Contents](#table-of-contents)
2. [Writing a Post](#writing-a-post)
3. [Change Infos](#change-infos)
   1. [Author](#author)
   2. [Contexts](#contexts)
   3. [Contact](#contact)
4. [Change Structure](#change-structure)
   1. [Navigation](#navigation)
   2. [Layouts](#layouts)
5. [So Simple Theme License](#so-simple-theme-license)

## Writing a Post

Adding a markdown file [`/docs/_posts`](docs/_posts) will result an addition of blog post.

Filename format should be **YYYY-MM-DD-Name_Of_The_Post.md**.

## Change Infos

### Author

Add/Modify your author info on [`/_data/authors.yml`](_data/authors.yml).

You can add profile images on [`images`](images) folder.

### Contexts

In [`/docs/`](docs/) folder, there are several markdown files for major pages, which is mostly accessible via navigator.

Contexts of [`About`](docs/about.md) and [`Publications`](docs/publications.md) can be edited easily by modifying thoses markdown files.

For changing the very first page of our website, you can edit [`index.md`](index.md) file.

### Contact

To change the individual author's contact, change [`/_data/authors.yml`](_data/authors.yml).

To change the kind of contact or its link of footer, change footer_links: part on [`_config.yml`](_config.yml).

## Change Structure

### Navigation

Add/Delete page(s) you want at [`/_data/navigation.yml`](_data/navigation.yml) file will result the change of top navigator bar.

### Layouts

Edit some html codes in [`/_layouts`](/_layouts) but BE CAREFUL; this may cause the malfunction of styles or format.

Its format and code is inherited from the so-simple-jekyll-theme.

## So Simple Theme License

[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg?style=flat-square)](https://raw.githubusercontent.com/mmistakes/so-simple-theme/master/LICENSE)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.6-blue.svg?style=flat-square)](https://jekyllrb.com/)
[![Ruby gem](https://img.shields.io/gem/v/jekyll-theme-so-simple.svg?style=flat-square)](https://rubygems.org/gems/jekyll-theme-so-simple)