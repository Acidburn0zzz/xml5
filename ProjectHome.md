# XML-ER #

A [XML Error Recovery Community Group](http://www.w3.org/community/xml-er/) has been started to work on [XML-ER](http://dvcs.w3.org/hg/xml-er/raw-file/tip/Overview.html). Feel free to participate there.

# XML5 #

The goal of this project is develop a proposal for **XML5**. A revised of XML that no longer follows the well-formedness principle but instead has a way of error handling that is closer to HTML, except that it is more predictable. This new version will be backwards compatible with XML 1.0 and XML 1.1 in a way that documents written in those languages (and don't rely on external DTD validation) will still work in XML5. The other way around is not necessarily true of course.

The idea is that having a non "draconian" version of XML would allow it be adopted more easily on the web as people tend to generate content using string concatenation which makes it very hard to guarantee "well-formed XML". It also allows for better competition in the mobile space where XML content is not always parsed using an XML parser by all players.