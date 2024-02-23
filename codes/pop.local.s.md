# POP.LOCAL.S Instruction
Pops value from stack into local.  
Short version.

> [!WARNING]  
> The locals indexation begins with 1!  
> `pop.local.s 0` cause an error

Attribute|Value
:-|:-:
Alias | `pop.local.s`
Introduced in | [v1](/v1)
Size | 2 = 1 + 1
Signature | `0x08`
Stack pop | [Var](/STACK_BEHAVIOUR.md#MoveVar)
Stack push| [None](/STACK_BEHAVIOUR.md#None)