This repository contains the pandoc-markdown source for the "[Clojure
- Functional Programming for the
JVM](http://java.ociweb.com/mark/clojure/article.html)" article.

To generate the html file, you'll need
[Pandoc](http://johnmacfarlane.net/pandoc/) installed. Then run this
command:

    pandoc -s -S --toc --css=styles.css --template=_tmpl.html -B before.html -o article.html article.md

It was originally written by Mark Volkmann from Object Computing, Inc.
It is now being updated by the Clojure community.
Thanks to all the contributors including
Sean Corfield, John Gabriele, stuntgoat, and Alex Miller.

A Chinese translation was created by James Xu
and is available at http://java.ociweb.com/mark/clojure/article_cn.html.
