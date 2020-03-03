# natas16

http://natas16.natas.labs.overthewire.org/

* What other shell tricks can we use? `$(echo hello)`.
* Can we combine this with normal text? Yes: `hell$(echo o)` or `$(echo s)hell`.
* We can run arbitrary commands, so we can probably test out password file... using our own grep.
* grep uses regular expressions, and `^` means to begin matching at the start of the string, so that you don't accidentally get the password from the middle.
* You might want to write a script to do some of the guessing for you.
