# Feedback solve

First, we see the website use feedback system.

![feed1](https://user-images.githubusercontent.com/43633395/145657801-ab1a1934-308c-4ff5-9693-0f73377da121.PNG)

Feedback, comments and login are know for a <a href="https://owasp.org/www-community/attacks/xss/"> XSS attack</a>. So, let's try to inspect element.

![feed1 5](https://user-images.githubusercontent.com/43633395/145657803-9d512d09-b6d3-420f-832a-422a65c262f6.PNG)

If the `onsubmit="return validate_form(this)"` protect against XSS attack that's ok else that's a vulnerability.
Let's write an basic injection `alert(1);` on an input.

![](https://user-images.githubusercontent.com/43633395/146208794-0b2c6a14-c4be-4eff-aee1-b789b824b95d.png)

We got it!

![feed3](https://user-images.githubusercontent.com/43633395/145657797-e59c22c8-1cb6-40b1-aab1-12de49825f08.PNG)

> <a href="../flag">flag</a> - <a href="../../level01">next</a>

