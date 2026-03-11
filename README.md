# lab-wardialing

This project uses Python and the requests library to check whether hostnames or IP addresses respond like web servers.

## Test

![test](https://github.com/MiaUrosevic/Lab6_wardial/actions/workflows/test.yml/badge.svg)

## Example Run

```bash
$ python3 -m doctest wardial. py -v
25 tests in 4
25 passed.
Test passed.

$ python3 wardial.py
scanning 127.0.0.0
scanning 127.0.0.1
scanning 127.0.0.2
scanning 127.0.0.3
...
```