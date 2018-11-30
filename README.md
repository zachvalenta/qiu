# OVERVIEW

<a href="https://asciinema.org/a/QLZgHjoIKusJYzpY2YwSSDaba" target="_blank"><img src="https://asciinema.org/a/QLZgHjoIKusJYzpY2YwSSDaba.png" alt="img" height="300px" align="right"/></a>

[httpie](https://httpie.org/) is already great!

`qiu` is a wrapper:

* for _local_ development 
* that makes common `httpie` functionality more terse

# INSTALL

* have Python 3
* put `qiu` on `$PATH`
* done  😌

# FLAGS

* `-pa`: URL path
* `-po`: port
* `-m`: HTTP method
* `-j`: path to `.json` file

# EXAMPLES

__GET__

```
# qiu
qiu -po 5000 -pa books

# httpie
http http://127.0.0.1:5000/books
```

__POST__

```
# qiu
qiu -po 5000 -pa books -m POST -j post.json

# httpie
http POST http://127.0.0.1:5000/books @json/post.json
```
