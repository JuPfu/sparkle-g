# sparkle-g
Automatically exported from code.google.com/p/sparkle-g

The SPARQL query language for RDF is designed to meet the use cases and requirements identified by the RDF Data Access Working Group in RDF Data Access Use Cases and Requirements.
sparkle-g (SPARQL Grammar) is a SPARQL ANTLR v3 cross-platform grammar.

----

*2009-11-28 2.0 Release is out*

Switched to Apache License 2.0 and proper Maven 2 build, check out the [http://sparkle-g.googlecode.com/svn/site/2.0/index.html 2.0] site

----

*2011-12-25 3.2 Release is out*

The sparkle-g project has released a pretty printer and syntactic validator for the [http://www.w3.org/TR/sparql11-query/ SPARQL 1.1 Query] and 
[http://www.w3.org/TR/2011/WD-sparql11-update-20110512/ Update Language] [http://www.w3.org/2001/sw/DataAccess/ http://sparkle-g.googlecode.com/svn/site/images/sw-sparql-green.png]. The pretty printer and syntactic validator is based on the [http://antlr.org/ ANTLR] framework for constructing recognizers, interpreters, compilers, and translators. The generation of the formatted output text relies on the [http://www.stringtemplate.org/ StringTemplate] template engine. [http://antlr.org/ ANTLR] and 
[http://www.stringtemplate.org/ StringTemplate] have both been designed and crafted by [http://www.cs.usfca.edu/~parrt/ Terence Parr], a professor of computer science at the [http://www.cs.usfca.edu/ University of San Francisco].

Support of Maven 3 build, check out the [http://sparkle-g.googlecode.com/svn/site/3.2/index.html 3.2] site

----

*2012-03-17 3.3 Release is out*

The modifications in the W3C Working Draft of 05 January 2012 are supported now:
 * SHA224 removed from hash function choices
 * Added functions STRBEFORE, STRAFTER, REPLACE
 * Define DATATYPE on language tag literals.
 * Aggregates allowed in ORDER BY clause
 * Lexer enhanced to allow backslash character escapes in prefixed names
 * Allow ASK to take solution modifiers
 * null to n occurences of the {{{AdditiveExpression}}} rule 

Support of Maven 3 build, check out the [http://sparkle-g.googlecode.com/svn/site/3.3/index.html 3.3] site

----

*2012-01-04 3.3.1 Release is out*

 * Several fixes with regards to rewriting and group template rules mostly concerning update rules.

 * Split of Sparql.g (combined lexer and parser grammar) in two distinct files {{{SparlLexer.g}}} (lexer grammar) and {{{SparqlParser.g}}} (parser grammar) for SparqlPrettyPrinter. The generated files remain the same! This might ease the construction of composite grammars (see: http://www.antlr.org/wiki/display/ANTLR3/Composite+Grammars)

 * Added queries from http://www.w3.org/TR/sparql11-update/#updateLanguage as testcases.

Support of Maven 3 build, check out the [http://sparkle-g.googlecode.com/svn/site/3.3.1/index.html 3.3.1] site

----

*2012-11-28 4.0 SPARQL Pretty Printer 4 beta based on Antlr V4.03b is out*

The sparkle-g project has released a pretty printer and syntactic validator for the [http://www.w3.org/TR/2012/PR-sparql11-query-20121108/ SPARQL Query Language] and 
[http://www.w3.org/TR/2012/PR-sparql11-update-20121108/ SPARQL Update Language], which is based on a beta version of [http://www.antlr.org/wiki/display/ANTLR4/Home Antlr V4].

Support of ant build.

Details on the Wiki SparklePrettyPrinterV4 page.

----

The Project Page is published on ANTLR grammar list, check it out on [http://www.antlr.org/grammar/1200929755392/index.html SPARQL] grammar page.
