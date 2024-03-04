rot13
=====

rot13 rotate letters by 13 place.

Example
-------

**Package**

	from rot13 import rot13

	print(rot13("hello"))

**Command**

	$ echo hello | rot13
	uryyb

	$ echo hello | rot13 | rot13
	hello

Install
-------

	$ pip install rot13

Bugs
----

- rot13 only rotate ascii characters.
