# json-urls-with-spaces

## About

On 2018-05-30, I filed a Mozilla Firefox bug - when showing JSON response containing URLs with unencoded spaces, the hover/click value is truncated at first space.

The bug can be found here: https://bugzilla.mozilla.org/show_bug.cgi?id=1465376

## Technically

db.json contains data for [My JSON Server](https://my-json-server.typicode.com/) fake server, which is used to reproduce the behavior.

- Direct response: https://my-json-server.typicode.com/leibrug/json-urls-with-spaces/urls
- Using fetch(): https://jsfiddle.net/ng5xqdg1/
