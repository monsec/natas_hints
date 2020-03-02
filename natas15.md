# natas15

http://natas15.natas.labs.overthewire.org/

* This calls for a different type of SQL injection...
* You could make your own script, or take advantage of [sqlmap](http://sqlmap.org/).
* Depending on how your connection is filtered, you might need to be a different agent, or use another connection.
* Try guessing what username exists.
* If you are told that the input is not dynamic by sqlmap, double check you are sending it correctly. Manually figure out what the "true" (found) and "false" (not found) response looks like and pass the `--string` parameter accordingly.
* Ensure you nudge sqlmap to try harder (more levels).
