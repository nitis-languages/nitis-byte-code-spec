# LOAD.S Instruction
Pushes local value onto stack.  
Short version.

> [!WARNING]  
> The locals indexation begins with 1!  
> `load.local 0` cause an error

Attribute|Value
:-|:-:
Alias | `load.s`
Introduced in | [v1](/v1)
Size | 2 = 1 + 1
Signature | `0x05` u8
Stack pop | [None](/STACK_BEHAVIOUR.md#None)
Stack push| [Var](/STACK_BEHAVIOUR.md#MoveVar)