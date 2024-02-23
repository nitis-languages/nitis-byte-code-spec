# BREAK Instruction
Inform a debugger that a breakpoint has been reached. 

> [!IMPORTANT]  
> This instruction is ignored when debug is disabled

Attribute|Value
:-|:-:
Alias | `break`
Introduced in | [v1](/v1)
Size | 1
Signature | `0x01`
Stack pop | [None](/STACK_BEHAVIOUR.md#None)
Stack push| [None](/STACK_BEHAVIOUR.md#None)


## Examples

```
method "x"
{
    push.i32 3
    push.i32 2
    break
    add
    ret
}
```
