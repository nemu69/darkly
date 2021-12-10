# Cookies solve

What are Cookies :

	Cookies are packets of data that a website uses to identify a visitor’s computer and use that visitor’s computer network.
	Cookies remember certain information about a visitor for instance,
 	and will use this information if the user re-visits the site.
#

First, we see the website cookies.

![cookie1](https://user-images.githubusercontent.com/43633395/145501359-4b2a1226-6502-4b89-8636-7e1e7c374278.PNG)

We see the name `i_am_admin` and the value (maybe encrypted) `68934a3e9455fa72420237eb05902327`.
So we decide to go on the <a href="dcode.fr">dcode.fr</a>

And after some research on the website, we find the decrypted part and try to unlock it.
The most rational word was decrypted in <a href="https://en.wikipedia.org/wiki/MD5">MD5</a> :

`false`

Ok, i_am_admin has a value false. We will use dcode for write `true` in MD5.
Let's replace the value by `b326b5062b2f0e69046810717534cb09` and refresh the page

We got it!

![cookie2](https://user-images.githubusercontent.com/43633395/145501370-9956b995-2325-449d-989d-3e98ad7946e0.PNG)


> <a href="../flag">flag</a> - <a href="../../level01">next</a>

