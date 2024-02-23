# NiBC Version №1

## Flow type
+ Next - executes, then executes next bytecode
+ Branch - may move to specific bytecode
+ Return - return control to the caller

Byte|Flow type|Name|Description
:-:|:-:|:-:|:-
`0x00`|Next|[`nope`](./codes/nope.md)|Does nothing
`0x01`|Next|[`add`](./codes/add.md)|Pops two integers from stack, then push result onto stack
