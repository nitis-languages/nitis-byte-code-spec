# LOAD Instruction
Pushes local value onto stack.

> [!WARNING]  
> The locals indexation begins with 1!  
> `load 0` cause an error

Attribute|Value
:-|:-:
Alias | `load`
Introduced in | [v1](/v1)
Size | 5 = 1 + 4
Signature | `0x04` u32
Stack pop | [None](/STACK_BEHAVIOUR.md#None)
Stack push| [Var](/STACK_BEHAVIOUR.md#MoveVar)