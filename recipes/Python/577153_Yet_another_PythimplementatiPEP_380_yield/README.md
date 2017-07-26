###Yet another Python implementation of PEP 380 (yield from)

Originally published: 2010-03-26 19:46:29
Last updated: 2010-04-25 23:08:07
Author: Arnau Sanchez

Any Python programmer knows how extremely powerful [generators](http://www.python.org/dev/peps/pep-0255/) are. Now (since version 2.5) Python generators can not only yield values but also receive them, so they can be used to build [coroutines](http://www.python.org/dev/peps/pep-0342/).