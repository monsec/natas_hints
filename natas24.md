# natas24

http://natas24.natas.labs.overthewire.org/

* If you are unfamiliar with strcmp-like functions, they return 0 if the strings are equal (otheriwse value depends on lexicographic order). The `!strcmp` is on the right track.
* The official PHP documentation does not mention this, but strcmp also return false-y values for other inputs. Google for strcmp vulnerabilities.
