py-slr
------

A simple SLR parser using python

Usage:
------
+ Store grammar in a file (all rule must be in format X->a, ie LHS and RHS seperated by -> and no | operator, use only single alphabet for each terminal and non-terminal eg: i for id)
+ Run
	python slr_short.py
+ Enter grammar file name
+ All GOTO and REDUCTION table is generated
+ Enter string to check
+ Parse table with result is shown
