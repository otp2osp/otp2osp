## Welcome to OTP 2 OSP (Open Telecom Platform to Open Server Platform)

This project is an effort to create a toolbox with libraries, software patterns and tools to build scalable server technology on top of Erlang OTP. 



### Let's create a platform with: 

- rebar3 as build tool 
- rebar3 plugins, like mix in elixir, to generate server behaviours  (like gen_tcp_server, gen_ssl_server, gen_udp_server).
- integrated community libraries/tools (define some patterns)  to solve common backend issues (just examples):

   * recon - production debug 
   * fuse, jobs, raterl - Circuit breaker and rate limiters
   * lager - logging framework
   * lhttpc - HTTP client  (we  have other alternatives)
   * poolboy, pooler, poolgirl - workers pools with and without back pressure
   * tsung, bashobench  - load testing
   * gpb, msgpack - binary protocols 
   * cowboy - RESTful API's 
   * rabbitmq, 0mq - message queue systems
   * and more...

- knowledge base and articles to learn about backend development .
