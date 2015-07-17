# 3-Jekyll Theme

This is a free 3 column theme based on Jekyll. Thank for the original [author](https://github.com/P233/3-Jekyll), we just forked and modified it. Just try and you will love to use it for blogging!

#Setup Guide

It's very easy to set up a new site.

1. Install Ruby and bundler
1. Fork this repo and clone it.
1.  Install Jekyll and all dependencies by cmd `bundle install`
1.  Run server by `bundle exec jekyll serve`

Then your site should be available at http://localhost:4000.
Let's create a new post by octopress.
Default command

> bundle exec octopress new post "Post Title"

Octopress will use the post scaffold to create a file in _posts.
But we prefer to specify a dir to hold the posts, and it will add this folder's name to the file's category.

> bundle exec octopress new post "Post Title" --dir posts

The category will apear on the sidebar of the site. Open the browser to check it.



#Customization

First you need personalize your site by editing `_config.yml`.
There are a lot variables in the file, and they can be called by {{ site.variable }} in the various _includes and _layouts.

###_layouts
This folder hold the layout you might use in your Front-matter.
And every layout will include some html by `{% include *.html %}`.

###_includes
The files included by layouts are placed in there.

###_templates
The octopress's scalfford is placed in this folder.