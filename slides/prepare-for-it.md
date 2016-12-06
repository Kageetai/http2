##  Prepare for it

- Prepare secure connection or make the move to TLS now
  - This should be your priority
- Prepare for HTTP/2 in your build process
  - create assets with optimizations mentioned before and without
- Check your user statistics for supported browsers
  - [CanIUse.com/HTTP2](http://caniuse.com/#feat=http2)
- Check your hosting
- Roll out HTTP/2 optimization

note:
    organize assets as they are needed, as this will prepare for when concatenation is obsolete and you will get best performance by managing resources
    for sharding certificates must be prepared to be valid for both hostnames as TLS will be necessary
    By comparing browser usage on your website with the support table on Can I Use, you can see what percentage of visitors would benefit from HTTP/2 optimization.
    of course check your servers if they provide support for HTTP2 and if you don't have control over that yourself, ask your providers
    and it's backwards-compatible so even updating earlier won't hurt the remaining users
    individual images and sprites
    data URI and normal images
