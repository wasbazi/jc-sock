JSON Socket's in C
==

This is my attempt to further understand how a C library would handle http
requests that parses a JSON body.

# Usage
Right now the program should be compiled and then run. Once running there will be a listener on port 8888, and it will wait for a connection and print the body of that request and then quit.

This can be seen if you run a curl, like so:

```bash
curl -X POST -H "Content-Type: application/json" -d '{"username": "xyz", "password": "abc"}' localhost:8888
```
