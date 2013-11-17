# DocuSS #

## What is it? ##

DocuSS is a tool to provide quality format to simple HTML documents. DocuSS adds margins, format, code highlighting, document metadata and automatic index.

## How it works? ##

DocuSS transforms the markup inside your browser and adds a set of CSS files. This document is using DocuSS, you can see the source code and how is transformed by inspecting the DOM.

## How can I use it? ##

Very simple: only the next line must be included in your 'head' section of your HTML document and all will work:

```
<script src="http://www.treeweb.es/ShareCode/preview/fc9ad45551a6e4b4d06e038fe9a6250b/js" type="text/javascript"></script>
```

## Improvements ##

### Version 0.2 ###

* Can use attribute 'lang' or 'language' to force a certain language inside a tag 'code'.
* Added a small margin to the document (this is good when the text fit to the width of the screen).
* Improved indentation style (numbers are coloured and targeted ones are coloured too) and functionality (now, titles have an hyperlink to itself).
* Added document title
* Added document metadata
* Improve style for code when print
* Search for hash and navigate to it
* Update hashes format

### 1.4.2Version 0.1 ###

* It is the first version.