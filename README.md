# HTTP/2.0 Main Information.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Pros.](#pros)
* [Cons.](#cons)
* [Help](#help)





## About.





## Documentation.





## Pros.
* Support multiplexed. Multiplexing over single connection.
* Support server push.
* Support compression(header & data).
* Is binary.
* Secure by default.
* Protocol negotiation during TLS(ALPN).





## Cons.
* Server Push can be abused when configured incorrectly.
* Can be slower when in mixed mode (backend is HTTP/2 but load balancer is HTTP/1.1 or vise versa).





## Help.
