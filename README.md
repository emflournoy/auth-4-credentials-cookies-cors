# Credentials, Cookies, and CORS Quiz.
## Coookieee! Om Nom Nom!

### Instructions
With your partner, in words both of you will understand 6 months from now, answer the following questions.

> How would you best summarize credentials when it comes to auth?

Credentials is using your username and password to login and see if you have access to the files you are requesting.
1) who are you?
2) prove it.
3) can you haz?

> Describe how cookies are exchanged between client and server.  Make sure you touch on the technical implementation of cookies.

The cookies are sent by the server and response header - they are key value pairs that allow you to keep temporary authorization or information between sessions.
Cookies are HTTP only and can only be accessed by the domain that set them unless given permissions otherwise (or unless they are unsecured cookies).

> From the perspective of a developer, name some basic strengths of using cookies and some weaknesses.

good: They don't take up a lot of space, allows for multiple page sessions, can add extra timeout security with persistent cookies
bad: they aren't always as secure - anything in document.cookies can be taken over public wifi or from ads on a site - session hijacking

> What is the difference between a session cookie and a persistent cookie?

Session cookie is deleted after the browser or window is closed.

Persistent cookies are deleted after a specified amount of time.

> What is your opinion of the same-origin policy?  Support your opinion with some evidence.

it's rather necessary even though it really sucks during Q1. it allows for more secure transmission of cookies and you're less likely to have your session hijacked. You are only allowed to access the information on the site if you have the same origin(protocol, host, and port) unless otherwise specified by the server. No one would want to use the internet if they had to log in on every page.

> Based on what you know, how would you explain CORS?

Cross-origin resource sharing =  Once you are logged in CORS allows you use other pages specified by the server to access cookies.
