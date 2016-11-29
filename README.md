# Halite visualization server

A local server to visualize Halite replay files.

## Usage

```
$ python viz_server.py -h
usage: viz_server.py [-h] [--port PORT] path

positional arguments:
  path         Directory containing replay files

optional arguments:
  -h, --help   show this help message and exit
  --port PORT  Specify alternate port [default: 8081]
```

To visualize a file named `test.hlt` in the replay folder, go to `http://localhost:8081/r/test`
