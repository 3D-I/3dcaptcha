About
----------------------------------------------------------------------
3DCaptcha is an easy to use captcha written in PHP. It features:

* A new approach to captchas, using human's spatial cognition
  abilities to differentiate humans from machines.
* It uses a markov-chain to generate words that resemble human
  language and are easy to type, yet avoid dictionary lookups.
* It's easy to implement.

Enjoy.



Installation
----------------------------------------------------------------------
3DCaptcha requires PHP4, with gd image support. To find out how to
install gd check out this URL:

http://php.net/image

You'll also need to add TrueType support.

By default, 3DCaptcha uses PHP's $_SESSION variable. If you have a
custom session handler, replace all calls to the $_SESSION variable.

To generate a word, include TextGen.php. This generates a text. To
display an image, add this HTML tag:

<img src="3DCaptcha.php" alt="captcha">

The php code will generate an image with the text in the $_SESSION
variable.



License
----------------------------------------------------------------------
3DCaptcha is released under GPLv3.

Contact
----------------------------------------------------------------------
http://www-personal.umich.edu/~mressl/3dcaptcha

Tell me what you think about 3DCaptcha, so it only gets better and
better!


