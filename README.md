# Googler

A simple client for Google Web Search API.

# Install

```
$ git clone git://github.com/thinkphp/googler.py.git
$ cd googler.py
$ python app.py
$ => output
```

# Usage

```
import sys
from googler import Google

google = Google('your-api-key')

print google.search(q='jQuery')
```


# License

MIT

