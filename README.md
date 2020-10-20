# truth-table

A simple program to create truth table in Discrete Math (cuz the author's too lazy to write them down)

## How-to

Complile the project with all .cpp files
`> gcc *.cpp -lstdc++ -o <PROGRAM_NAME>`

Then simply run
`> ./<PROGRAM_NAME>`

## Operations

Currently, there're 5 operators: AND `^`, OR `v`, XOR `+`, IMPLY `>` and "if and only if" IFF `~`. There's also a negation operator `-`.

Variable names can vary all lowercase and uppercase ascis (or even other symbols :D), but of course let alone lowercase `v` cuz that's an operator.

Write the expression in the correct form (pls), then let the magic works.

## Example:
```
> ./main

> a + b ^ -(a v b)

|a|b|avb|-(avb)|b^-(avb)|a+b^-(avb)
+-+-+---+------+--------+----------
|0|0|0  |1     |0       |0
+-+-+---+------+--------+----------
|0|1|1  |0     |0       |0
+-+-+---+------+--------+----------
|1|0|1  |0     |0       |1
+-+-+---+------+--------+----------
|1|1|1  |0     |0       |1
+-+-+---+------+--------+----------
```

## Disclaimer

I haven't finished the project so there're lots of things to do, especially error-handling, so pls be gentle with this babe :<
