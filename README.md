# A Material for Mkdocs Blog Template

The purpose of the template in this repository is to give you a starting point
for setting up a blog that makes use of features that Material for MkDocs
provides and of selected integrations with other plugins that are of specific
relevance to running a blog.

It reflects the results you get by going through the [blog tutorials] in the
documentation. 

[blog tutorials]: https://squidfunk.github.io/mkdocs-material/tutorials#blogs

## Requirements

The to use the all the features this template uses, you need the [Insiders
Edition] of Material for MkDocs but it should be easy enough to strip it down so
that it works with the public version.

[Insiders Edition]: https://squidfunk.github.io/mkdocs-material/insiders/

You will also need to install the [mkdocs-rss-plugin].

[mkdocs-rss-plugin]: https://github.com/guts/mkdocs-rss-plugin

## Using it

This the repository is a [template repository], so you can create as many forks 
of it as you like and your repository will contain only a single commit to start 
with, instead of the whole history of the template. Also, you can create a 
private repository from this template (while forks inherit the visibility settings 
from the original).

[template repository]: https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template

Simply hit the `Use this template` button. You can set the specifics of your new 
repository from there.

[repository that contains this template]: https://github.com/mkdocs-material/create-blog


## Project layout

The following shows the layout of the files in this template. Note that you can
configure Material for MkDocs to use a different layout, this is simply the
default.

```
mkdocs.yml              # The configuration file.
docs/
    index.md            # The documentation homepage.
    blog/               # The directory that all blog content goes into (first blog instance)
        posts/          # the place to put your posts
        author/         # Author profiles
        .authors.yml    # Author information to be added to posts (shared betwe
ext/                    # Directory that contains code for the custom slugs
hooks/                  # Directory for a hook that adds social media share buttons
```

