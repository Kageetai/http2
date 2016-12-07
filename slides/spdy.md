##  SPDY

- [research project by 2 engineers at Google in 2009](http://googleresearch.blogspot.co.uk/2009/11/2x-faster-web.html)
- multiplexing request across single TCP connection
- client can prioritize assets to be send back first
- compress and reduce HTTP headers
- server-side push of assets
- HTTPS as requirement
- not meant to replace HTTP, just modify how request and responses are sent
- support first in many browser (and servers) but soon dropped in favor of HTTP2

