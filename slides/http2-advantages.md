##  HTTP2 <!-- .element: class="section-title" -->

# Advantages

- Multiplexing and concurrency <!-- .element: class="fragment" -->
- Stream dependencies/prioritizing <!-- .element: class="fragment" -->
- Header compression <!-- .element: class="fragment" -->
- Server push <!-- .element: class="fragment" -->

note:
    so first what' so great about this new player on the block/
    - Several requests can be sent in rapid succession on the same TCP connection, and responses can be received out of order - eliminating the need for multiple connections between the client and the server
    - the client can indicate to the server which of the resources are more important than the others, have higher priority
    - HTTP header size is drastically reduced
    - The server can anticipate and send resources the client has not yet requested
