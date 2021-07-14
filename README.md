# nbase

Command line utility to convert freely between any two number
bases with a maximum base of 36.

The default usage 

     $ nbase n
	 
displays n in four number-basses: binary, octal, decimal and hex.

Special syntax used for common input bases.

     %nnn   - binary  %1100
	 0nnn   - octal   01234
	 nnn    - decimal (default)
	 0xnnn  - hex    0xFF
	 
Other bases are specified by prefixing the number with b^ for base b.

     7^1234 - for base 7
	 
Use the --out option to set explicit output base.

    $ nbase --out 13  7^n
	
Displays base 7 n in base 13.






	 
	 

