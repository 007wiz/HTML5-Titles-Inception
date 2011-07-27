From [HTML5Doctor's article about Outlines](http://html5doctor.com/outlines/) :

> The document outline is the structure of a document, generated by the document’s headings, form titles, table titles, and any other appropriate landmarks to [map out the document](http://www.w3.org/TR/2002/REC-UAAG10-20021217/guidelines#tech-provide-outline-view). [...] The outlining algorithm has been clearly defined in the [HTML5 spec](http://dev.w3.org/html5/spec/Overview.html#outlines).

It allows web developers to use only `<h1>`s in their content thanks to a hierarchy of sectioning element containing them. This is really useful with Content Management Systems that may generate the same HTML source for several usages.

Unfortunately, most browsers still don't have default CSS rendering for such multi level `<h1>`s.

This is where [HTML5 Titles Inception](https://github.com/nhoizey/HTML5-Titles-Inception) tries to help, with a (not so) little CSS that you can extend.

Fortunately, tools such as [LESS](http://lesscss.org/) and [SASS](http://sass-lang.com/) exist, so that you don't have to put the whole CSS mess into your files.

Be careful about performance through when using such complex selectors in your CSS.