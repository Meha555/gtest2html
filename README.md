# gtest2html
Convert googletest xml output to html

Use with any xslt processor e.g.

```bash
$ xsltproc -o test_detail.html gtest2html.xslt test_detail.xml
```
- gtest2html2.xsl 不带样式
- gtest2html.xslt 带有样式

The css stylesheet was borrowed from here: 
http://red-team-design.com/practical-css3-tables-with-rounded-corners
