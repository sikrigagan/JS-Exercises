What is JavaScript?
===

History
--
* **1995**: Project started by [Brendan Eich](https://en.wikipedia.org/wiki/Brendan_Eich "Know more at Wikipedia") at Netscape with scripting language called **Mocha**, which was later renamed to **LiveScript**. Then, Netscape entered into development alliance with Sun Microsystems and later name of LiveScript was changed to **JavaScript** to capitalize buzz of Java at that time.
* **1996**: With increasing popularity of JavaScript 1.0, Microsoft decided to invest in new competiting browser called *Internet Explorer (IE)* introducing its own JavaScript implementation called **JScript**. This major step by Microsoft started journey of development of JavaScript as a language.
* **1997**: Now, with Microsoft's implementation of JScript and Netscape's implementation of JavaScript there were 2 different versions of this scripting language which caused standardization issues so, JavaScript 1.1 was submitted to the European Computer Manufacturers Association (ECMA) as a proposal and Technical Committee #39 (TC39) was assigned to standardize the syntax and semantics of a general purpose, cross-platform, vendor-neutral scripting language which resulted in **ECMA-262**, a standard defining a new scripting language
named **ECMAScript**. Since then all browsers use ECMAScript as a basis for their JavaScript implementations.


JS Implementation
--
JS implementation is made up of 3 parts:

1. The Core (*ECMAScript*)
+ DOM (Document Object Model)
+ BOM (Browser Object Model)


**ECMAScript**: *language defined in ECMA-262*
* It is not directly consumed rather it acts as a base to define more robust scripting languages.
+ Web browsers are just one kind of host environment in which as ECMAScrip implementation may exist.
+ It defines following parts of further implemented scripting language:
    + Syntax
    + Types
    + Statements
    + Keywords and Reserved Words
    + Operators
    + Objects
+ The most recent version (edition) of ECMAScript is editon 5 and was released in 2009. Quick glance to changes made over different editions is as below:
    + Edition 1:
        + All referenced to browser-specific code were removed.
        + Platform dependency for Objects was removed.
        + Unicode standard was included to support other languages.
    + Edition 2:
        + Most editorial changes were made for ISO/IEC-16262 standard.
    + Edition 3:
        + Better support for error handling, `try-catch` (exception handling) was included.
        + New and improved control statements were included.
        + Support for regular expressions was included.
    + Edition 4:
        + In this edition complete overhaul was made to whole ECMA-262 by including:
            + Strong types varibles
            + New Statements and Data Structures
            + True Classes and Classical Inheritence
            + New and improved ways to interact with data
    + Edition 5: (*Also known as **ECMAScript 3.1***)
        + This edition primarily focused on clarifying percieved ambiguities in previous versions.
        + Introducing additonal functionalites to language like:
            + Support for native JSON object.
            + Methods for Inheritance and advanced propery definition.
            + Strict mode was included to check how ECMAScript engines interpret and execute code.


**Document Object Model (DOM)**:
* It is an API for XML that was extended for use in HTML, and maps out entire web page as a hierarchy of nodes.
    + For example, DOM map (*DOM Tree*) for following web page will be:
    ```html
    <html>
        <head>
            <title>Sample Page</title>
        </head>
        <body>
            <p>Hello World!</p>
        <body>
    </html>
    ```
    DOM Tree:

    ![DOM Model](https://s31.postimg.org/6xnt3a9e3/Screen_Shot_2016_07_03_at_5_54_47_PM.png)
+ Manipulation can be done on all these elements/nodes present in web page and new nodes can also be added with the help of DOM API.
+ DOM is important aspect of a web page as it acts as intermediary between code and renderer.
+ Different levels of DOM:
    + Level 1:
        + It became W3C recommendation in October 1998.
        + It consisted of 2 modules and they are explained as below:
            + **DOM Core**: It provided a way to map the structure of XML-based document to allow easy access and manipulation of the document.
            + **DOM HTML**: It extended DOM Core by adding HTML specific objects and methods.
    + Level 2:
        + It was extension to DOM from *Level 1* and added support for:
            + Mouse and UI events
            + Ranges and Traversals
            + Support and Manipulation of CSS through object interfaces.
        + Below are new modules added in Level 2:
            + **DOM Views**: It is responsible for interfaces to keep track of various views of document.
            + **DOM Style**: It is responsible for interfaces to handle CSS based styling of DOM elements.
            + **DOM Range & Traversal**: It is responsible for interfaces to handle manipulation of DOM tree.
    + Level 3:
        + It extends DOM with uniform load and save document methods.
        + It provide new methods for DOM validation.
        + In this level, DOM Core is extended to support all of XML 1.0 including XML Infoset, XPath & XML Base.
    + Other DOM's: Apart from three levels discussed above, each DOM adds methods and interfaces unique to a particular language support:
        + SVG (Scalable Vectore Graphics)
        + MathML (Mathematical Markup Language)
        + SMIL (Synchronized Multimedia Integration Language)