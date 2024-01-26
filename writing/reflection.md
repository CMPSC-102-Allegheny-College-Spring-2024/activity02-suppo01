# Data Types

TODO: Please remove the TODO markers and notes from this file
so that the final document is written in a professional fashion
suitable for publication. If you have questions about how to
structure, format, and write this document, please ask for a
preliminary assessment of your work in advance of the deadline.

## Molly Suppo

## Program Output

### What is the output from running the following commands?

- `python demonstrate-variable-limitations.py`

```cmd
The value of a feasible number is 115792089237316195423570985008687907853269984665640564039457584007913129639936

The value of another feasible number is 179769313486231590772930519078902473361797697894230657273430081157732675805500963132708477322407536021120113879871393357658789768814416622492847430639474124377767893424865485276302219601246094119453082952085005768838150682342462881473913110540827237163350510684586298239947245938479716304835356329624224137216
```

- `python compare-variables.py`

```cmd
1.0 is not the same as 1.1
1.0 is the same as 1.0
.33333 + .33333 + .33333 is not equal to 1
.33333333333 + .33333333333 + .3333333333 is not equal to 1
The value of 1/3 is 0.3333333333333333
0.3333333333333333 + 0.3333333333333333 + 0.3333333333333333 is equal to 1
1/3 + 1/3 + 1/3 is equal 1
```

## Program Questions

### Why is it not feasible to perform the computation `2**2**100`?

It is not feasible to perform the computation `2**2**100` because the computer can only represent so much information. The binary that the computer uses to represent the numbers used and found in these computations have a limit on how much they can represent. Once that limit is reached, a number cannot be represented. An example would be with what is refered to as 8 bits, a smaller measurement used to describe information. 8 bits can represent 256 values, or anywhere from 0 to 255 values. With this in mind, the unfeasible computation mentioned above must go over that limit, making it unfeasible for the computer.

### What is the value of `1/3` according to the Python language? Why?

The value of `1/3` according to the Python language is `0.3333333333333333`. This is because there is no "common sense" to round it, so instead, the value is represented goes out as long as the computer will represent it for us to see. Because it does not have the common sense to round or recognize other answers as "close enough" it only recognizes the value I provided as `1/3`. I imagine it follows the same kind of logic that a claculator would given that it also returns `1/3` as the longer repeated decimal.

### Why is the value of `.33333 + .33333 + .33333 == 1` equal to `False`?

The value of `.33333 + .33333 + .33333 == 1` is equal to `False` because the computer does not have the "common sense" to round here. It gets close to 1, but will not equal 1 in this case. In addition, the computer also has an interesting property of floating point values it follows that humans typically do not. Floating point addition tends to opperate almost like a limit in these types of scenarios. The result comes close to what we anticipate the answer to be, but it does not reach it.

(Did you remember to add your name?!)