# RandomHeaders

Python Module that generates fake user agents with a locally saved DB.  All the other Fake User Agent programs that I've seen scrape from a website that frequently goes down.

This is useful for webscraping, and testing programs that identify devices based on the user agent.

## Getting Started

```
>>> import RandomHeaders
>>> header = RandomHeaders.LoadHeader()
>>> print header
{'User-Agent': 'Mozilla/5.0 (X11; U; Linux i686; en-US) AppleWebKit/532.0 (KHTML'}
```