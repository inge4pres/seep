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
  1. interaction acceptance
  2. transaction definition
  3. exchange of informations
  4. transaction validation

##### Fast
Using the standard protocol implemetation you will have a way of communicating with any SEEP user at the speed of your internet connection. Once implemented the protocol can be fully automated to activate partners and communications without human interaction.

### What does EDI means?
Electronic Data Interchange: it is a set of standards defined to help business interoperate in the exchange of documents, usually using digitalisation of information. 
[EDI page on Wikipedia]: http://en.wikipedia.org/wiki/Electronic_data_interchange

### Is SEEP an alternative EDIFACT?
No: SEEP is a standard to define communication and trasactions, not content of informations exchanged. EDIFACT may be one of the payload delivered through SEEP.

### How does SEEP work?
##### Non-technical answer
You use the software provided or develop a software on your own ehich is able to comply with protocol specifications and use this software to communicate with other SEEP users. The software will handle everything following the protocol guidelines but if any of your partner is using an extended version on SEEP you should be able to implement the same functionalities to interact with him. 

##### More technical infos
SEEP's implementation goes from the session layer of the ISO/OSI stack and up, the rest of the stack is left to TCP/IP and the underlying infrastructure; standard implementation software are provided and can be used to initiate a development process around the protocol.

### Where to go from here?
You should read the protocol specifications and once finished have a look at the implementation examples to have a better understand on how to start using the protocol.
