# LOAD.ARG Instruction
Pushes argument value onto stack.

> [!WARNING]  
> The argument indexation begins with 1!
> `load.arg 0` means load `self`

Attribute|Value
:-|:-:
Alias | `load.arg`
Introduced in | [v1](/v1)
Size | 5 = 1 + 4
Signature | `0x02`
Stack pop | [None](/STACK_BEHAVIOUR.md#None)
Stack push| [Var](/STACK_BEHAVIOUR.md#MoveVar)


## Examples

```
method "x"
    return value [stdlib.nlib]:"Standard.Int32"
    parameters
    (
        value [stdlib.nlib]:"Standard.Int32" "value"
    )
{
    load.arg 1          # Load argument by index
    pop
    load.arg "value"    # Load argument by name
    ret
}
```
