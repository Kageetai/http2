###  What needs to be changed <!-- .element: class="section-title" -->

##  Concatenating

- while developing the files are kept separated for the ease of the developers
- again the user has to download all of the merged files, even if unneeded
- with HTTP2 you can serve up only the code that the visitor needs

note:
    another technique just to limit the number of request to the server
    but the build process concatenates them together, which also complicates the build process itself
    whole browser cache needs to be purged to for single (line) changes or with a short expiry date
