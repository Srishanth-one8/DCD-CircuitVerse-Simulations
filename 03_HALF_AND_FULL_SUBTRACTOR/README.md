# Half Subtractor and Full Subtractor

Digital circuit simulations created using CircuitVerse.

## Half Subtractor

A Half Subtractor subtracts one binary input from another binary input.

### Inputs
- A = Minuend
- B = Subtrahend

### Outputs
- Difference
- Borrow

### Boolean Expressions

Difference = A XOR B

Borrow = NOT A AND B

### Truth Table

| A | B | Difference | Borrow |
|---|---|------------|--------|
| 0 | 0 |     0      |   0    |
| 0 | 1 |     1      |   1    |
| 1 | 0 |     1      |   0    |
| 1 | 1 |     0      |   0    |

---

## Full Subtractor

A Full Subtractor subtracts two binary inputs along with a Borrow In.

### Inputs
- A = Minuend
- B = Subtrahend
- Bin = Borrow In

### Outputs
- Difference
- Bout = Borrow Out

### Boolean Expressions

Difference = A XOR B XOR Bin

Borrow Out = (NOT A AND B) OR (NOT A AND Bin) OR (B AND Bin)

### Truth Table

| A | B | Bin | Difference | Bout |
|---|---|-----|------------|------|
| 0 | 0 |  0  |     0      |  0   |
| 0 | 0 |  1  |     1      |  1   |
| 0 | 1 |  0  |     1      |  1   |
| 0 | 1 |  1  |     0      |  1   |
| 1 | 0 |  0  |     1      |  0   |
| 1 | 0 |  1  |     0      |  0   |
| 1 | 1 |  0  |     0      |  0   |
| 1 | 1 |  1  |     1      |  1   |

---

## Tool Used

CircuitVerse

## Project

Half Subtractor and Full Subtractor

## Status

Completed
