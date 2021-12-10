# Survey solve

Go to HOST/index.php?page=survey

First, we see a classic survey.

<p>
    <img src="https://user-images.githubusercontent.com/43633395/145650926-98f6f84e-1ad6-4623-a3dc-24d084ff4494.PNG" width=55% />
</p>


<!-- ![survey1](https://user-images.githubusercontent.com/43633395/145650926-98f6f84e-1ad6-4623-a3dc-24d084ff4494.PNG) -->

So, he said `Youre voice is important for us !!!`. Try to inspect element.

<p>
    <img src="https://user-images.githubusercontent.com/43633395/145650925-ba47259e-8776-4916-9d81-750f68919c56.PNG" width=150% />
</p>

We see two vulnerabilities :

- onchange of select attribute can suffer <a href="https://owasp.org/www-community/attacks/xss/"> XSS attack</a>
- the value of option attribute can changed and make a overflow

Let's try the second option.

We got it!

![survey3](https://user-images.githubusercontent.com/43633395/145650923-04bf2fac-7f9c-4141-bd82-2df035922bda.PNG)

> <a href="../flag">flag</a> - <a href="../../level01">next</a>


