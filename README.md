#AltusMods
The Language accepted so far:
-> The parser is a recursive Descent parser that parses the following CFG:
Block - Block | Statement,
Statement - =Expression,
Expression - operand operator Expression | operand

Where :
operand, operator and = are all terminals. (The rest are non terminals.)
