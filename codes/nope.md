# NOPE Instruction
Does nothing. Used as memory aligner.

Attribute|Value
:-|:-:
Alias | `nope`
Introduced in | [v1](/v1)
Size | 1
Signature | `0x00`
Stack pop | [None](/STACK_BEHAVIOUR.md#None)
Stack push| [None](/STACK_BEHAVIOUR.md#None)


## Examples

```
method "x"
{
    nope # does nothing
    ret
}
```
