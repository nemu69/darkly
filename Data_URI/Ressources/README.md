# DataURI solve

By clicking on the nsa logo you will find the address:

```HOST/index.php?page=media&src=nsa```

Note that the image is loaded by a `src=nsa' identifier, so it is a [URI](https://www.guru99.com/url-vs-uri-difference.html)
With a URI you can access a resource without accessing its location, so using a [data-URI](https://developer.mozilla.org/en-US/docs/Web/HTTTP/Basics_of_HTTP/Data_URIs) will allow us to use a script.

`data:[<MIME type>][;base64],<data>`
- MIME type : file type (text/html, text/plain, ...)
- base64 : optional
- data : the resource to be loaded

We know the type of file, we only have the data (our script):

We must now encode it in base64 since it will end up in our URI:
`PHNjcmlwdD5hbGVydCgndG90bycpPC9zY3JpcHQ+`

Now that we have all the data, we can replace `nsa' with our data-URI:
`HOST/index.php?page=media&src=data:text/html;base64,PHNjcmlwdD5hbGVydCgndG90bycpPC9zY3JpcHQ+`

# How to avoid it?

Use a database instead of an ID to load resources!

We got it!

![survey3](https://user-images.githubusercontent.com/43633395/145650923-04bf2fac-7f9c-4141-bd82-2df035922bda.PNG)

> <a href="../flag">flag</a> - <a href="../../level01">next</a>
