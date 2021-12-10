# RecoverPassword solve

Go to HOST/index.php?page=survey

First, we see a classic survey.

IMG

So, he said `Youre voice is important for us !!!`. Try to inspect element.


IMG
<p>
    <img src="https://user-images.githubusercontent.com/43633395/145496636-26d3d884-bac3-4f04-9694-c34580d828fe.png" width=200% />
</p>

We see two vulnerabilities :
	- onchange of select attribute can suffer XSS attack
	- the value of option attribute can modified ( make a overflow :) )

Let's try the second option.

We got it!


IMG
![recover3](https://user-images.githubusercontent.com/43633395/145496689-834fb86a-88d5-469b-a834-cefe1ec94880.png)

> <a href="../flag">flag</a> - <a href="../../level01">next</a>

