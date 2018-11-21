# Flask WAF
A Flask WAF plugin for CTFers.

Using *Python 3.6*.

Designed and developed by [Prinny](https://github.com/PrinnyRay).


## Usage
```shellcode
pip install -r requiremtns  # no third-party packages required
```
```python
# adding the following code to your entrance file.
from Flask_WAF import WAF
app = Flask(__name__)
WAF(app)
```


## RoadMap

> - [ ] Configuration Module
> - [ ] Operating Mode Module
>     - [ ] Monitoring Mode
>     - [ ] Protecting Mode
> - [ ] Interception Module
> - [ ] Malicious Contents Detection Module 
>     - [ ] SQL Injection Detection
>     - [ ] XSS Injection Detection
> - [ ] White/Black list
>     - [ ] Bans according to IPs
>     - [ ] Bans according to HTTP Headers
>     - [ ] Bans according to query strings
>     - [ ] Bans according to POST contents
>     - [ ] Trusted files and paths
> - [ ] Log Module
> - [ ] Mirror Code for Python 2.x