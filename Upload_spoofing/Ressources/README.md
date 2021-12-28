# Upload_spoofing solve

By clicking on the nsa logo you will find the address:

```HOST/index.php?page=upload```

There is a form allowing to upload an image file on the site.
When trying to send a file that does not have an extension corresponding to an image file the site responds with "Your image was not uploaded."

However, you can force the upload of unauthorized files like "main.c" with CURL :

`curl -F 'Upload=' -F 'uploaded=@main.c;type=image/jpeg' http://192.168.56.102/?page=upload`
- -F : -F/--form <name=content> Specify HTTP multipart POST data (H)
- Upload= : submit element 
- uploaded=@main.c : the file to be loaded in file input
- type=image/jpeg : Content-Type

# How to avoid it?

There are many ways to prevent this. Check [this page](https://www.owasp.org/index.php/Unrestricted_File_Upload#Prevention_Methods_.28Solutions_to_be_more_secure.29) for a methods list

We got it!

`The flag is : 46910d9ce35b385885a9f7e2b336249d622f29b267a1771fbacf52133beddba8`

> <a href="../flag">flag</a> - <a href="../../level01">next</a>
