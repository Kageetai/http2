### Ye good ol' Times <!-- .element: class="section-title" -->

## Sharding

![sharding](resources/sharding.png)
> [https://http2-explained.haxx.se/](https://http2-explained.haxx.se/)


note:
    tries to serve your assets from as many hosts as possible
    in the beginning HTTP1 only allowed 2 TCP connections per host
    techniques to use new host names were used to circumvent this restriction
    limitation is higher nowadays but sharding still in use
    today the top 300K URLs in the world need on average 40(!) TCP connections to display the site
    another variant of that technique is used when specific cookie-free host names are used just to serve static images and decrease cookies, as these have been growing significantly over the years
