# 4 Bit Adder and 1-to-4 Demux Circuit Explanation

An explanation about 4 Bit Adders and 1-to-4 Demux Circuits and how they work.

## 4 Bit Adder

A 4 bit adder adds two 4 bit binary numbers. It produces a 4 bit sum and a carry-out bit if the result needs an extra bit. For example, `0011` (3) + `0101` (5) = `1000` (8).

It works by connecting four full adders together. Each full adder adds two input bits and a carry-in it. The carry moves from the lowest bit to the highest bit, like carrying a number when adding by hand. For basic addition, the first carry-in is set to `0`.

##  1-to-4 Demux

A 1-to-4 demux sends one data input to one of four outputs. Two select bits choose which output gets the input, while the other outputs stay at `0`.

It uses logic gates to combine the data input with the select bits or their inverted values. Only the selected path passes the input through. For example, if the input is `1`. and the select bits are `10`, then `y2` is `1` and all other outputs are `0`.
