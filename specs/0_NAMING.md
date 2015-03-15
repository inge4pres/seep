# __SEEP NAMING__
### Naming components to be used in SEEP

A standard method for naming any part of a SEEP related software will be used.
Description of naming convention is as follows.

##### Naming constants
A constant is a value which is never changed in the same layer of the protocol and may remain unchanged thruogh all the protocol implementation stack.

Naming of constant will follow this rule:

_A constant name is an alphanumeric uppercase word, preceded and followed by the underscore symbol "_"._

Example of a constant:

\_CONSTANTNAME_

##### Naming obects
An object is a mutable container of information, valid only at a single layer of the stack. Isolation of objects will prevent naming overlapping of objects in different layer to interfere wih the ease of implementation

Naming of objects will follow this rule:

_An object name is an alphanumeric word with only the first charachter uppercase and ther rest lowercase._

Example of an object:

Object123

