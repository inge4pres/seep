# __SEEP CONNECTIVITY__
### Definition of communication used in SEEP

As mentioned before SEEP uses only a part of the ISO/OSI stack, leaving the rest to TCP/IP.
It is not in the scope of this document to detail the ISO/OSI stack but steps described in this document are enough to implement the connectivity layers used by SEEP.

##### Definition for connectivity
_RADD_: the remote address of the transasction actor; format: IPv4, IPv6, DNS.
_LADD_: the local address of the actor, as seen by the transactio party; format: same as _RADD_.
_TLSV_: the version of TLS protocol to be offered to clients connecting as transaction party; format: string, possible value are "10", "11", "12".
_CIPH_: the cipher suite used for connection; format: string, following RFC values.

