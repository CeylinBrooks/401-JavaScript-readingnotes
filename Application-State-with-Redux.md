What are the advantages of storing tokens in “Cookies” vs “Local Storage”
Local Storage
Pros: It's convenient.

It's pure JavaScript and it's convenient. If you don't have a back-end and you're relying on a third-party API, you can't always ask them to set a specific cookie for your site.
Works with APIs that require you to put your access token in the header like this: Authorization Bearer ${access_token}.
Pros: The cookie is not accessible via JavaScript; hence, it is not as vulnerable to XSS attacks as localStorage.

If you're using httpOnly and secure cookies, that means your cookies cannot be accessed using JavaScript. This means, even if an attacker can run JS on your site, they can't read your access token from the cookie.
Source (Links to an external site.)

 

It's automatically sent in every HTTP request to your server.
Explain 3rd party cookies.
- data allows you to learn about your web visitor's overall online behaviors, such as websites they frequently visit, purchases, and interests that they've shown on various websites.

How do pixel tags work?
 typically single pixel, transparent GIF images that are added to a web page. Even though the pixel tag is virtually invisible, it is still served just like any other image you may see online.

 

cookies- are arbitrary pieces of data, usually chosen and first sent by the web server, and stored on the client computer by the web browser.
authorization-  is the function of specifying access rights/privileges to resources, which is related to general information security (Links to an external site.) and computer security (Links to an external site.), and to access control (Links to an external site.) in particular
access control- is the selective restriction of access to a place or other resource (Links to an external site.)[1] (Links to an external site.) while access management (Links to an external site.) describes the process.
conditional rendering- a term to describe the ability to render different user interface (UI) markup if a condition is true or false
