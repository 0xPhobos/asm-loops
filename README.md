# ASM Loop's Test

### x10 with JMP 

```
MOV cl 10
L1:
<LOOP-BODY>
DEC CL
JNZ L1
```

### Basic LOOP Instruction

```
LOOP label
```

ECX registers the loop count

### ECX should register value. Counter reaches 0

```
mov ECX,10
l1:
<loop body>
loop 11
```
