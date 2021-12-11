# Redirect solve

First, we see the website use url redirection (Facebook, Twitter, Instagram).

IMG

So, let's try to inspect element.

IMG

We can change URL redirection, that's a vulnerability because an attacker can use <a href="https://owasp.org/www-community/attacks/xss/"> XSS attack</a> or could create a link and phish users.
Let's change this URL for print the flag.

We got it!

IMG


> <a href="../flag">flag</a> - <a href="../../level01">next</a>
