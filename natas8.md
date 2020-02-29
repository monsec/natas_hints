# natas8

http://natas8.natas.labs.overthewire.org/

* The server uses the PHP programming language. You can run PHP code by installing PHP on your own device, or by using an online interpreter like https://paiza.io/en/projects/new (some disable certain functions for security reasons).
* Google for the name of each function within encodeSecret to figure out what it does.
* You should write an inverse function to decode the secret. You can do this in PHP, or by making a recipe with [CyberChef](https://gchq.github.io/CyberChef/).
* You need to "unwrap" the functions in the corrrect order - e.g. since bin2hex is applied last, you need to undo it first.
