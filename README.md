# Old Personal Site

## About

My first website from 2003 when I was a student at [Cornell University](https://www.cornell.edu/) originally hosted at people.cornell.edu/jt96.

The content for the site was managed in `xml` files and `html` was generated using an `xslt` template that managed the header, footer, and site metadata.

### Built With

- HTML, CSS, XML, [RDF](https://www.w3.org/RDF/)
- [Apache Xalan-J](http://xalan.apache.org/xalan-j/index.html), XSLT
- [Java](https://www.java.com/)

### Prerequisites

- Java Development Kit 11+
- [Apache Maven](https://maven.apache.org/)

## Installation and Build

In `stylesheets/xml2html.xsl` modify this line to change it to the root of where the html pages will be

`<xsl:variable name="root">https://justunsix.github.io/old-people-cornell-edu-jt96</xsl:variable>`

Execute this Maven command to build and generate the site from the `xml` files.

```
mvn install
mvn compile exec:java
```

Transformation progress will be output to the console.

## Usage

Visit the website at the root you set in the installation.

A live version is at GitHub pages: <https://justunsix.github.io/old-people-cornell-edu-jt96/>

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

[Find me on GitHub](https://github.com/justunsix/)

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

Site was extracted from the [Wayback Machine](https://archive.org/web/) 2004 and 2005 archives and restored with relative links and text based content formats where feasible.

Original Wayback Machine archive links:

- [Search of URLs at http://web.archive.org/web/*/http://www.people.cornell.edu/pages/jt96/*](http://web.archive.org/web/*/http://www.people.cornell.edu/pages/jt96/*)
- <http://web.archive.org/web/20050306232558if_/http://www.people.cornell.edu/pages/jt96/index.html>
- <http://web.archive.org/web/20050306232558if_/http://www.people.cornell.edu/pages/jt96/stylesheets/artemis.css>
- <http://web.archive.org/web/20050306232558if_/http://www.people.cornell.edu/pages/jt96/stylesheets/xml2html.xsl>
- <http://web.archive.org/web/20050306232558if_/http://www.people.cornell.edu/pages/jt96/images/artemis_tower.jpg>
- <http://web.archive.org/web/20050307024538if_/http://www.people.cornell.edu/pages/jt96/siteinfo/sitemap.html>
- <http://web.archive.org/web/20050307023004if_/http://www.people.cornell.edu/pages/jt96/resources/index.html>
- <http://web.archive.org/web/20050307010854if_/http://www.people.cornell.edu/pages/jt96/resources/articles.html>
- <http://web.archive.org/web/20050407054953if_/http://www.people.cornell.edu/pages/jt96/resources/oscoms.html>
- <http://web.archive.org/web/20050307010603if_/http://www.people.cornell.edu/pages/jt96/resources/academic.html>
- <http://web.archive.org/web/20050307023400if_/http://www.people.cornell.edu/pages/jt96/resources/projects/cs490/cs490.html>
- <http://web.archive.org/web/20050307023714if_/http://www.people.cornell.edu/pages/jt96/resources/projects/cs501/cs501.html>
- <http://web.archive.org/web/20050407060237if_/http://www.people.cornell.edu/pages/jt96/resources/docs/texts.html>
- <http://web.archive.org/web/20041223193634if_/http://www.people.cornell.edu/pages/jt96/resources/docs/essays.html>
- <http://web.archive.org/web/20050306232419if_/http://www.people.cornell.edu/pages/jt96/explore/writeme.html>
- <http://web.archive.org/web/20050306232204if_/http://www.people.cornell.edu/pages/jt96/explore/links.html>
- <http://web.archive.org/web/20041226052701if_/http://www.people.cornell.edu/pages/jt96/explore/personalink.html>
- <http://web.archive.org/web/20050306231424if_/http://www.people.cornell.edu/pages/jt96/aboutme/index.html>
- <http://web.archive.org/web/20050306231058if_/http://www.people.cornell.edu/pages/jt96/aboutme/bio.html>
- <http://web.archive.org/web/20050307071604if_/http://www.people.cornell.edu/pages/jt96/aboutme/coursework.html>
- <http://web.archive.org/web/20050306231658if_/http://www.people.cornell.edu/pages/jt96/aboutme/interests.html>
- <http://web.archive.org/web/20050307002541if_/http://www.people.cornell.edu/pages/jt96/aboutme/readinglist.html>
- <http://web.archive.org/web/20050306231936if_/http://www.people.cornell.edu/pages/jt96/aboutme/resume.html>
- <http://web.archive.org/web/20050307024056if_/http://www.people.cornell.edu/pages/jt96/siteinfo/index.html>
