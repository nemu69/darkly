# Feedback solve

First, we see the website use feedback system.

IMG

Feedback, comments and login are know for a <a href="https://owasp.org/www-community/attacks/xss/"> XSS attack</a>. So, let's try to inspect element.

IMG

If the `onsubmit="return validate_form(this)"` protect against XSS attack that's ok else that's a vulnerability.
Let's write an basic injection `alert(1)` on an input.

IMG

We got it!

IMG

> <a href="../flag">flag</a> - <a href="../../level01">next</a>