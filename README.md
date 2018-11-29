# OVERVIEW

[httpie](https://httpie.org/) is already great!

`qiu` is a wrapper:

* for local development 
* that makes common `httpie` functionality more terse

📍 finish 'examples', repo, README, LICENSE, video, rm from `util-scripts`, https://github.com/search?q=httpie+wrapper

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

```

__PUT__

```
# qiu
qiu -po 5000 -pa books/0812972864 -m PUT -j json/put.json
# httpie

```
