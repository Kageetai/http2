### Ye good ol' Times <!-- .element: class="section-title" -->

## Spriting

![spriting](resources/spriting.jpg)
> [https://http2-explained.haxx.se/](https://http2-explained.haxx.se/)

note:
    Spriting is the process of combining a lot of small images into one huge one
    then JavaScript or CSS is used to only show the part of the image that is currently needed
    this was done because of the aforementioned latency issues in HTTP1
    it was faster to just request one big image instead of many small ones
    but this makes even sites that only need one or two pictures, download the all of them
    browser cache needs to be refreshed entirely every time
