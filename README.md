# GHER documentation

This wiki is meant to contain all the information that does not fit specific projects, software tools or personal pages.

Typically the content of the [Software section](http://modb.oce.ulg.ac.be/mediawiki/index.php/Software) of the previous wiki.
Once a section has been moved to the current wiki, the corresponding link should be added in the former wiki.

## Conversion from mediawiki

To convert from `mediawiki` format to `markdown`, use [pandoc](http://pandoc.org/) conversion tool.   
An example for the conversion of the Python section:
```bash
pandoc -f mediawiki -t markdown Python.wiki -o Python.md
```
where `Python.wiki` is a file whose content is obtained as a copy/paste of the mediawiki source

## Other contents

**Projects:** should be listed at http://labos.ulg.ac.be/gher/projects/ with a link to the project web page.
**Personal pages:** links at http://labos.ulg.ac.be/gher/people/.
**Software tools:** links to [github](https://github.com/gher-ulg) from http://labos.ulg.ac.be/gher/software-2/.




