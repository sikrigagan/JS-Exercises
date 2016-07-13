Using `<script>` Element
===


* It is primary method of inserting JavaScript in HTML web page.
+ `<script>` element was created by Netscape and first introduced in Netscape Navigator 2; later it was added to formal HTML specification and was made standard to insert JavaScript in HTML web page.
+ `<script>` element is divided into six parts, and they are explained as below:
    + **`type`**: It is optional and used to specify the type (*MIME type*) of scripting language being used by code block.
    + **`src`**: It is optional and only used to declare an external file that contains code to be executed.
    + **`language`**: It is deprecated now and was used to indicate the scripting language used by code block like JavaScript, JavaScript 1.2 or VBScript etc.
        + Now, most of browsers ignore this attribute and it should not be used.
    + **`async`**: It is optional and used to instruct that script should begin downloading immediately but should not affect other actions on tha page.
        + It is valid only for external scripts.
    + **`defer`**: It is optional and used to indicate that execution of script can be safely postponed until after all document's content has been completely parsed and displayed.
        + It is also valid only for external scripts.
    + **`charset`**: It is optional and not used much. It is used to specify character set for the script being used.