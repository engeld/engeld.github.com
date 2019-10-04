GitHub-Repository for my [dev-blog](https://engeld.github.io)
=============================================================
This repository contains my [jekyll](http://jekyllrb.com/)-based [dev-blog](https://engeld.github.io).

Installation
------------
The local installation is pretty straightforward - simply clone the repo:

    $ git clone git@github.com:engeld/engeld.github.io.git
    $ cd engeld.github.io/
    
Local Blogging
--------------
Whenever I'm writing a post, I write a draft first:

    $ cd engeld.github.io/
    $ vim _drafts/example-post.markdown

The advantage of using draft is that they are still under version control (and thus turn up in Github)
but won't turn up on the blog until published,

Publishing
----------
Once a post is finished and polished, I "publish" it by moving, renaming and `git push`-ing:

    $ cd engeld.github.io/
    $ mv _drafts/example-post.markdown _posts/2013-00-00-example-post.markdown
    $ git add _posts/2013-00-00-example-post.markdown
    $ git commit -m "publish example post"
    $ git push origin master


Links
-----

- [Github Pages, the system I'm using](https://pages.github.com/)
- [The underlying static site generator used by Github Pages](https://jekyllrb.com/)
