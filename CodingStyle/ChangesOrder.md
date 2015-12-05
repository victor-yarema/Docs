# Changes order
This document describes recommended code changes order.
- Refactoring
	- Redundant content (delete)
		- Files
		- Code in files
		- Comments
			- Language specific documentation
			- Those that state something that is well known (documented)
		- Ws (whitespace)
			- Trailing
			- Indentation
			- Multiple consequent ws chars between non-ws chars in line
			- Automated formatting
	- Ws (whitespace)
		- Break (wrap) long line
		- Add line break between items in long list
	- Invert conditional statements to achieve *early exit* and decrease indentation
	- Spread code to multiple separate files (*single responsibility*)
- Implementation
