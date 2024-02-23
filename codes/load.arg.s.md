# LOAD.ARG.S Instruction
Pushes argument value onto stack.  
Short version.

> [!WARNING]  
> The argument indexation begins with 1!  
> `load.arg.s 0` means load `self`

Attribute|Value
:-|:-:
Alias | `load.arg.s`
Introduced in | [v1](/v1)
Size | 2 = 1 + 1
Signature | `0x03` u8
Stack pop | [None](/STACK_BEHAVIOUR.md#None)
Stack push| [Var](/STACK_BEHAVIOUR.md#MoveVar)


## Examples

```
method "x"
    return value s32
    parameters
    (
        value s32 "value"
    )
{
    load.arg.s 1          # Load argument by index
    pop
    load.arg.s "value"    # Load argument by name
    ret
}
```