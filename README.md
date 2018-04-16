# Workshop "Unicode and UTF-8": Exercise

_12.04.2018,
Jonas Sternisko, ADITION technologies_

## Solution Guideline

Hand in your solution by
1. Create a fork of this repository
2. Put your code inside a directory "<YOUR_USERNAME>"
3. Create a merge request

The solutions will be discussed Monday at 16:00, Konferenzraum 1.OG.

## Exercise 1: UTF-8 Encoding Scheme

Manually encode your name with UTF-8. The result should be a sequence ob binary octets. If your name does not contain any special characters, replace at least two characters with fancy forms. For example, “Jonas” can become “Jôñàŝ”.

## Exercise 2: UTF-8 Encoding Scheme

Write a function in a programming language of your choice which displays a unicode character as a sequence of bytes. Test it against the things you did manually. Try not to use any built-in functionality, but do it on your own.

## Exercise 3:

Get the file `titles.txt`. Inspect it with `xxd` (or `xxd -b`). Can you guess the encoding of the document? Hint: It has a fixed size of 8 bits per word.

Write a function that reads a sequence of binary and outputs the corresponding UTF-8 character. Use the function to convert the document to UTF-8.

Now google for command line tools which could do this for you and try at least two.

## Exercise 4: UTF-8 and URL-Encoding

Check Wikipedia for URL-encoding. Why do we need URL-encoding at all? can we not send UTF-8 in the first place?

Write a function which reads a URL-encoded string and outputs the UTF-8 representation. Use your function to convert the strings in `referrers.txt` to UTF-8 strings .
