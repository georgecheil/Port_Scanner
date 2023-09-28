# port_scanner
This is a port scanning tool made with Python 

The program can scan for open ports for a given IP address or a domain name.

It can scan multiple targets at once 

It can grab the banner from open ports

To use the IPy library, install with pip
```python
pip3 install IPy 
```



To import the code in to python script follow the example below 

```python
import port_scanner

ip = '192.168.1.1'

port_scanner.check_target(ip, 100)
```
