###  What needs to be changed <!-- .element: class="section-title" -->

##  Sharding

- again HTTP requests are cheap in the world of HTTP/2
- so the before mentioned sharding is entirely obsolete
- no need for addtional domain names to get more possible connections
- development overhead can be removed
- could even hinder performance as it creates additional TCP connections and hinders HTTP/2 from prioritizing resources

