# __SEEP__
## Secure Extensible EDI Protocol
##### A way of exchanging informations with your business partners defining your own format and relying on strong authentication and forward secrecy to ensure confidentiality of transactions.

### Features
##### Secure
Any actor uses asymmetric encryption to ensure the veridicity of sender and complete confidentiality of the message.

##### Extensible
Any transaction between 2 actors may be extended beyond the basic transaction specifications enabling the implementation of custom defined transactions between according parties.

##### Easy
The basic implementation is defined in 4 stages:
  1. interaction acceptance and confirmation
  2. transaction definition
  3. exchange of informations
  4. transaction validation

##### Fast
Using the standard transaction implemetation you will have a way of communicating with any SEEP user at the speed of your internet connection. Once implemented the protocol can be fully automated with any system integration to activate partners and communications without human interaction.

### What does EDI means?
Electronic Data Interchange: it is a set of standards defined to help business interoperate in the exchange of documents, usually using digitalisation of information. 
[EDI page on Wikipedia]: http://en.wikipedia.org/wiki/Electronic_data_interchange

### Is SEEP an alternative EDIFACT?
No: SEEP is a standard to define communication and trasactions, not content of informations exchanged.

### How does SEEP work?
##### Non-technical answer
You develop a software to comply with protocol specification and start using this software to communicate with other SEEP users.

##### More technical infos
SEEP defines the implementation from the session layer of the ISO network stack and up, the rest of the stack is left to TCP/IP and the underlying layers.
