# Translating XML to HTML using a Schema (XSD) and Stylesheet Transformation (XSLT)
Question 2 implements an XML schema (stored in Q2.xsd) for an collection of websites which host various videos. It includes things like the URL, reliability, and video library of each website recorded. Q2.xml provides an example implementation of the XML schema and Q2.xsl is a stylesheet specification used to convert the Q2.xml to Q2.html.

Use the command:

xsltproc Q2.xsl Q2.xml -o Q2.html;

to generate the html.