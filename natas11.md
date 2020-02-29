# natas11

http://natas11.natas.labs.overthewire.org/

* This requires some basic cryptography skills.
* Decode the base64 and look at the raw bytes, probably through hex.
* Have a look at what canges when the color changes.
* `plaintext XOR key = ciphertext` implies `ciphertext XOR key = plaintext`, but also `ciphertext XOR plaintext = key`.
* The key repeats over and over, so you can just apply it over and over. Again, [CyberChef](https://gchq.github.io/CyberChef/) is pretty good at this stuff. Remember that normal characters that should be treated as text are generally known as ASCII or UTF8.
* Smaller passwords for testing out XOR are better. Also try "rotating" the password e.g. `abcd` to `bcda`.
* Craft your own encrypted cookie.
