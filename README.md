# brainfuck_compiler
Compiler for the language brainfuck 

usage = "python3 ./brainfuck.py filename.bf"
or:
  import brainfuck
  code = "+++[>+++<-]>."
  brainfuck.evaluate(code)

> - move memory pointer right
< - move memory pointer left
. - print ascii character of value at current memory location
, - replace value in memory location with value for inputed ascii character
[ - open loop
] - close loop

Loops: they will end when the value at the currnt memory location id zero at the end of each run

eg: 
"hello"
+[----->+++<]>+.---.+++++++..+++.
