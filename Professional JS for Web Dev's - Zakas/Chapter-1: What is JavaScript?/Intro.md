What is JavaScript?
===

History
--
* **1995**: Project started by [Brendan Eich](https://en.wikipedia.org/wiki/Brendan_Eich "Know more at Wikipedia") at Netscape with scripting language called **Mocha**, which was later renamed to **LiveScript**. Then, Netscape entered into development alliance with Sun Microsystems and later name of LiveScript was changed to **JavaScript** to capitalize buzz of Java at that time.
* **1996**: With increasing popularity of JavaScript 1.0, Microsoft decided to invest in new competiting browser called *Internet Explorer (IE)* introducing its own JavaScript implementation called **JScript**. This major step by Microsoft started journey of development of JavaScript as a language.
* **1997**: Now, with Microsoft's implementation of JScript and Netscape's implementation of JavaScript there were 2 different versions of this scripting language which caused standardization issues so, JavaScript 1.1 was submitted to the European Computer Manufacturers Association (ECMA) as a proposal and Technical Committee #39 (TC39) was assigned to standardize the syntax and semantics of a general purpose, cross-platform, vendor-neutral scripting language which resulted in **ECMA-262**, a standard defining a new scripting language
named **ECMAScript**. Since then all browsers use ECMAScript as a basis for their JavaScript implementations.
<!-- end of History -->
---
JS Implementation
--
JS implementation is made up of 3 parts:
1. The Core (*ECMAScript*)
+ DOM (Document Object Model)
+ BOM (Browser Object Model)

<br/>
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
<!-- end of ECMAScript (48)-->