# RecoverPassword solve

Go to HOST/index.php?page=recover

What are Cookies ?

`Cookies are packets of data that a website uses to identify a visitor’s computer and use that visitor’s computer network. Cookies remember certain information about a visitor– for instance, items placed in a shopping cart on an e-commerce website – and will use this information if the user re-visits the site.`

First, we see the website cookies.

IMG

We see the name `i_am_admin` and the value (maybe encrypted) `68934a3e9455fa72420237eb05902327`.

So we decide to go on the <a href="dcode.fr">dcode.fr</a>

And after some research on the website, we find the decrypted part and try to unlock it.
The most rational word was decrypted in <a href="https://en.wikipedia.org/wiki/MD5">MD5</a> :

false

Ok, i_am_admin has a value false. We will use dcode for write `true` in MD5
Let's replace the value by `b326b5062b2f0e69046810717534cb09` and refresh the page

We got it!

IMG

> <a href="../flag">flag</a> - <a href="../../level01">next</a>

