## XML Schema for XHTML5 (HTML5 Polyglot)
Validation schema for XHTML5, based on [Olivier Ishacian's draft] (http://grepcode.com/file/repo1.maven.org/maven2/com.googlecode.l10n-maven-plugin/l10n-maven-plugin/1.5/xhtml5.xsd?av=f)

Extended with support for [microdata](http://en.wikipedia.org/wiki/Microdata_%28HTML%29), SVG and MathsML

NOTE: The schema is not able to handle data-* attributes due to limitations of the W3C's XML schema specification

##Usage
Validate XHTML5 files against `xhtml5_with_microdata.xsd` 

##Known issues
Validation of arbitrary data-* attributes is not possible due to limitations by the W3C XML schema specification
