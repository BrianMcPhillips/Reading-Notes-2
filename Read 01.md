JS Templates and Array .forEach method
    -Template literals are string literals allowing embedded expressions. You can use multi-line strings and string interpolation features with them.
    -They were called "template strings in prior editions before he Es6 specification
    -We have already been using template literals in vanilla JS. They allow you to create a single string with backticks while also being able to insert variables into the string
    -Strings in javascript have been historically limited, lacking the capabilities one might expect coming from languages like Python or Ruby. ES6 template strings introduce a way to define strings with domain specific languages.
    -Template strings use backticks rather than the single or double quotes we're used to with regular strings.
    - One of the first real benefits is string substitution. Substitution allows us to take any valid Javascript expression
    -String substitution, one of the real benefits of template strings is string substitution. You can have variables be the substition or even concatenate two variables together.
    -Multiline Strings, need a backslash they allow for the string to be placed on two lines in html.
    -Expressions the ${} syntax allows us to put an expression in it and it will produce the value.
    -HTML templates, with the ability to have multi line strings and use template expressions to add content into a string it makes it very easy to have HTML templates in code.
    -forEach() calls a provided callback function once for each element in an array in ascending order. It is not invoked for index properties that have been deleted or are unintialized. The range of Elements processed by forEach() is set before the first invocation of callback. Elements which are appended to the array after the call to forEach() begins will not be visited by callback.
    When to use a loop over forEach(), for each comes with a little caveat It only works on arrays. So if you want to actually count, forEach probably isnt your friend. lodash is a library for javascript it helps you do a lot of common things.