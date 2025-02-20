# Tcl Subtle Syntax Error

This repository demonstrates a common, yet subtle, error in Tcl code involving conditional returns within procedures.  The `badproc` procedure contains a syntax error that can lead to unexpected behavior.

## Bug Description
The `bug.tcl` file contains a Tcl procedure that intends to return variable `b` if variable `a` is equal to 1, otherwise it should return variable `a`. However, due to a syntax error, it doesn't function correctly.

## Solution
The `bugSolution.tcl` file presents the corrected version of the procedure, highlighting the fix.

## How to run
1.  Clone this repository.
2.  Run each Tcl file using a Tcl interpreter (e.g., `tclsh`).