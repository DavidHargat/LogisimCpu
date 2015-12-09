# LogisimCpu

Logisim is a free tool used to design (and simulate) digital logic circuits.

http://www.cburch.com/logisim/

This repository contains a WIP processor I'm designing in Logisim.

### Run

In order to load this project, simply start up Logisim, and open `CPU.circ`.

### Instructions

```

POINTER = byte register
*       = dereference
ADDRESS = parameter

INSTRUCTIONS

Jump to *POINTER
Jump to VALUE

Jump to VALUE if *POINTER!=0

Add value to *POINTER
Add *ADDRESS to *POINTER

Subtract value from *POINTER
Subtract ADDRESS from *POINTER

Set POINTER to VALUE
Set POINTER to *ADDRESS

Set *POINTER to VALUE
Set *POINTER to *ADDRESS

```


:
