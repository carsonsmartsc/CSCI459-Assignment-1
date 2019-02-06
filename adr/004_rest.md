# REST Capabilities and Overview

# Status: accepted

# Context: 

REST stands for representational state transfer which is an architecture that allows web services to use web sources using stateless operations. This means that no information is retained by the sender and the receiver. 

# Decision:

Wordpress by default is not stateless and is aware of the user and the information being transferred to and from the user. There is a Wordpress plugin to make the system stateless but require a lot of configuration. 

# Consequences: 

Transferring to a stateless system would provide more scalability and faster throughput but it is unnecessary for this class application. 

