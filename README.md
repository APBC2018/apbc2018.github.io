APBC2018 web site
========================

This site is powered by [Github Pages](https://pages.github.com/) with [Jekyll](http://jekyllrb.com/).

How To Modify
----------------

We can write web pages by the Markdown format. For example, ``index.md`` will be
converted into ``index.html`` by ``jekyll`` automatically when it is pushed into
the repository.

We can control the order of navigation menu in ``_data/nav.yml``.

We can preview the site by local Jekyll engine, which can be built as folllows:

```
rbenv install 2.4.2
rbenv local 2.4.2
gem install jekyll
gem install jekyll-paginate
jekyll server
```


CNAME Configuration
----------------

GitHub Pages uses ``CNAME`` file for a custom domain.
In our site, it contains a line as follows:

```CNAME
apbc2018.bio.keio.ac.jp
```

