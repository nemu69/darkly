# RecoverPassword solve

Go to HOST/index.php?page=recover

First, we see a recover password, but without an e-mail/username input.

![recover1](https://user-images.githubusercontent.com/43633395/145496533-c7f2d818-d26b-496b-be40-e70982c3cfee.png)

So, try to inspect submit button element.

<p>
    <img src="https://user-images.githubusercontent.com/43633395/145496636-26d3d884-bac3-4f04-9694-c34580d828fe.png" width=200% />
</p>

We see the `webmaster e-mail`, that's a vulnerability. Let's change this e-mail for print the flag.

We got it!

![recover3](https://user-images.githubusercontent.com/43633395/145496689-834fb86a-88d5-469b-a834-cefe1ec94880.png)

> <a href="../flag">flag</a> - <a href="../../level01">next</a>

