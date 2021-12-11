# Redirect solve

First, we see the website use url redirection (Facebook, Twitter, Instagram).

![redire1](https://user-images.githubusercontent.com/43633395/145657906-47793398-4555-4684-956b-f59d7b78f1b7.PNG)

So, let's try to inspect element.

![redire2](https://user-images.githubusercontent.com/43633395/145657908-3f07a42c-d2d4-4952-97dd-280d9c37b7b1.PNG)

We can change URL redirection, that's a vulnerability because an attacker can use <a href="https://owasp.org/www-community/attacks/xss/"> XSS attack</a> or could create a link and phish users.
Let's change this URL for print the flag.

We got it!

![redire3](https://user-images.githubusercontent.com/43633395/145657907-43d36eda-bca5-4619-b5c5-1791637dd439.PNG)


> <a href="../flag">flag</a> - <a href="../../level01">next</a>
