---
title: "Front End Questions"
questions:
- question: "What's the difference between an expression and a statement?"
  answer: "In a computer language, a group of words, numbers, and operators that performs a specific task is a statement. Statements are made up of one or more expressions. An expression is any reference to a variable or value, or a set of variable(s) and value(s) combined with operators."
- question: "How many types of expressions are in the following statement: a = b * 2;?"
  answer: "2 is a literal value expression. b is a variable expression, which means to retrieve its current value. b * 2 is an arithmetic expression, which means to do the multiplication. a = b * 2 is an assignment expression, which means to assign the result of the b * 2 expression to the variable a (more on assignments later)."
- question: "How often and when is JavaScript compiled?"
  answer: "It's typically asserted that JavaScript is interpreted, because your JavaScript source code is processed each time it's run. But that's not entirely accurate. The JavaScript engine actually compiles the program on the fly and then immediately runs the compiled code."
- question: "What is CORS? How does it work?"
  answer: "Cross-origin resource sharing (CORS) is a mechanism that allows many resources (e.g., fonts, JavaScript, etc.) on a web page to be requested from another domain outside the domain from which the resource originated. It’s a mechanism supported in HTML5 that manages XMLHttpRequest access to a domain different.

CORS adds new HTTP headers that provide access to permitted origin domains. For HTTP methods other than GET (or POST with certain MIME types), the specification mandates that browsers first use an HTTP OPTIONS request header to solicit a list of supported (and available) methods from the server. The actual request can then be submitted. Servers can also notify clients whether “credentials” (including Cookies and HTTP Authentication data) should be sent with requests."
---
