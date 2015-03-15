# __SEEP CONNECTIVITY__
### Definition of communication used in SEEP

As mentioned before SEEP uses only a part of the ISO/OSI stack, leaving the rest to TCP/IP.
It is not in the scope of this document to detail the ISO/OSI stack but steps described in this document are enough to implement the connectivity layers used by SEEP.

##### Definition of connectivity constants

_RADD_: the remote address of the transasction actor; format: IPv4, IPv6, DNS.
_LADD_: the local address of the actor, as seen by the transactio party; format: same as _RADD_.
_CIPH_: the cipher suite requested for connection; format: string, following [RFC5246 values](http://tools.ietf.org/html/rfc5246/ "TLS protocol implementation").
_SSID_: the SEEP ID of the user initiating the transaction; format: alphanumeric lowercase.
_SRID_: the SEEP ID of the user which the transaction is destined to; format: alphanumeric lowercase. 

##### Definition of connectivity
//TODO
