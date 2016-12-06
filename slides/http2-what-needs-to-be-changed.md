##  What needs to be changed

- HTTP2 requires TLS meaning secure connection for everything
- [Google uses secure connections as a ranking signal](https://googlewebmastercentral.blogspot.co.uk/2014/08/https-as-ranking-signal.html)
- browsers are starting to flag non-https websites as ‘not secure’
- so moving to HTTPS should be priority now

note:
    consider audience/visitors and the status of their browsers 
    we can basically stop a lot of the additional work we did before 
    TLS/encryption would be the first and maybe hardest step for most sites with the need for certificates etc.
    some HTML5 features, such as geolocation, will be unavilable without a secure connection
