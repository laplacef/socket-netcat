# socket-netcat

`socket_netcat` is a Python implementation of the `netcat` command using the `socket` library.

## Usage

```python
from socket_netcat import netcat

response = netcat(hostname="foo.bar", port=9000, content="Please respond!")
print(response)
```
