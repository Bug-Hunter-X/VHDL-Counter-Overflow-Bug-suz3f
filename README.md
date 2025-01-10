# VHDL Counter Overflow Bug

This repository demonstrates a common but subtle bug in VHDL code: integer overflow in a counter. The `counter` entity is designed to count from 0 to 15. However, a simple increment operation without checking for the maximum value will lead to an unexpected result or simulation failure when the counter reaches 15.

The `bug.vhdl` file contains the erroneous code.  The corrected version is in `bugSolution.vhdl`.  The bug is explained in detail in the `bug.vhdl` file comments.