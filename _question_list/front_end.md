---
title: "Front End Questions"
questions:
- question: "What's the difference between an expression and a statement?"
  answer: "In a computer language, a group of words, numbers, and operators that performs a specific task is a statement. Statements are made up of one or more expressions. An expression is any reference to a variable or value, or a set of variable(s) and value(s) combined with operators."
  link: "https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch1.md"
- question: "How many types of expressions are in the following statement: a = b * 2;?"
  answer: "2 is a literal value expression. b is a variable expression, which means to retrieve its current value. b * 2 is an arithmetic expression, which means to do the multiplication. a = b * 2 is an assignment expression, which means to assign the result of the b * 2 expression to the variable a (more on assignments later)."
  link: "https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch1.md"
- question: "How often and when is JavaScript compiled?"
  answer: "It's typically asserted that JavaScript is interpreted, because your JavaScript source code is processed each time it's run. But that's not entirely accurate. The JavaScript engine actually compiles the program on the fly and then immediately runs the compiled code."
  link: "https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch1.md"
- question: "What is CORS? How does it work?"
  answer: "Cross-origin resource sharing (CORS) is a mechanism that allows many resources (e.g., fonts, JavaScript, etc.) on a web page to be requested from another domain outside the domain from which the resource originated. It’s a mechanism supported in HTML5 that manages XMLHttpRequest access to a domain different. CORS adds new HTTP headers that provide access to permitted origin domains. For HTTP methods other than GET (or POST with certain MIME types), the specification mandates that browsers first use an HTTP OPTIONS request header to solicit a list of supported (and available) methods from the server. The actual request can then be submitted. Servers can also notify clients whether “credentials” (including Cookies and HTTP Authentication data) should be sent with requests."
  link: "https://www.toptal.com/web/interview-questions"
- question: "Explain the basic structure of a MIME multipart message when used to transfer different content type parts. Provide a simple example."
  answer: "Each MIME message starts with a message header. This header contains information about the message content and boundary. In this case Content-Type: multipart/mixed; boundary=frontier means that message contains multiple parts where each part is of different content type and they are separated by --frontier as their boundary. Each part consists of its own content header (zero or more Content- header fields) and a body. Multipart content can be nested. The content-transfer-encoding of a multipart type must always be 7bit, 8bit, or binary to avoid the complications that would be posed by multiple levels of decoding. The multipart block as a whole does not have a charset; non-ASCII characters in the part headers are handled by the Encoded-Word system, and the part bodies can have charsets specified if appropriate for their content-type."
  link: "https://www.toptal.com/web/interview-questions"
- question: "Consider the following JavaScript code that is executed in a browser: function startAjaxQueue(){ for (var i = 0; i < 50; i++){  	executeAjaxCallAsync();  }};Assuming that executeAjaxCallAsync() uses a standard XmlHttpRequest asynchronously to retrieve data from server, how many concurrent HTTP requests would you expect to be created by this loop?"
  answer: "Number of concurrent HTTP requests and XmlHttpRequest is limited in all browsers. Specific limitations are different depending on browser type and version. For example, according to Mozilla Developer Network Firefox 3 limits the number of XMLHttpRequest connections per server to 6 (previous versions limit this to 2 per server).Having this mind, the number of concurrent HTTP requests created in this loop would never (by default) be larger than 6, and the browser would therefore execute this loop in chunks."
  link: "https://www.toptal.com/web/interview-questions"
- question: "Explain the difference between stateless and stateful protocols. Which type of protocol is HTTP? Explain your answer."
  answer: "A stateless communications protocol treats each request as an independent transaction. It therefore does not require the server to retain any session, identity, or status information spanning multiple requests from the same source. Similarly, the requestor can not rely on any such information being retained by the responder. In contrast, a stateful communications protocol is one in which the responder maintains “state” information (session data, identity, status, etc.) across multiple requests from the same source. HTTP is a stateless protocol. HTTP does not require server to retain information or status about each user for the duration of multiple requests. Some web servers implement states using different methods (using cookies, custom headers, hidden form fields etc.). However, in the very core of every web application everything relies on HTTP which is still a stateless protocol that is based on simple request/response paradigm."
  link: "https://www.toptal.com/web/interview-questions"
- question: "Describe the key advantages of HTTP/2 as compared with HTTP 1.1."
  answer: "HTTP/2 provides decreased latency to improve page load speed by supporting: Data compression of HTTP headers Server push technologies Loading of page elements in parallel over a single TCP connection Prioritization of requests An important operational benefit of HTTP/2 is that it avoids the head-of-line blocking problem in HTTP 1."
  link: "https://www.toptal.com/web/interview-questions"
- question: "What is a “MIME type”, what does it consist of, and what is it used for? Provide an example."
  answer: "MIME is an acronym for Multi-purpose Internet Mail Extensions. It is used as a standard way of classifying file types over the Internet. Web servers and browsers have a defined list of MIME types, which facilitates transfer of files of a known type, irrespective of operating system or browser. A MIME type actually has two parts: a type and a subtype that are separated by a slash (/). For example, the MIME type for Microsoft Word files is application/msword (i.e., type is application and the subtype is msword)."
  link: "https://www.toptal.com/web/interview-questions"
---

cehsu/c2669dcf600ba1f1c4e106e5a965e16e

