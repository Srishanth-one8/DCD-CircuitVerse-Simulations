# Half Adder and Full Adder

Digital circuit simulations created using CircuitVerse.

## Half Adder

A Half Adder adds two binary inputs.

### Inputs
- A
- B

### Outputs
- Sum
- Carry

### Boolean Expressions

Sum = A XOR B

Carry = A AND B

### Truth Table

| A | B | Sum | Carry |
|---|---|-----|-------|
| 0 | 0 |  0  |   0   |
| 0 | 1 |  1  |   0   |
| 1 | 0 |  1  |   0   |
| 1 | 1 |  0  |   1   |

---

## Full Adder

A Full Adder adds three binary inputs.

### Inputs
- A
- B
- Cin (Carry In)

### Outputs
- Sum
- Cout (Carry Out)

### Boolean Expressions

Sum = A XOR B XOR Cin

Cout = (A AND B) OR (Cin AND (A XOR B))

### Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
| 0 | 0 |  0  |  0  |  0   |
| 0 | 0 |  1  |  1  |  0   |
| 0 | 1 |  0  |  1  |  0   |
| 0 | 1 |  1  |  0  |  1   |
| 1 | 0 |  0  |  1  |  0   |
| 1 | 0 |  1  |  0  |  1   |
| 1 | 1 |  0  |  0  |  1   |
| 1 | 1 |  1  |  1  |  1   |

---

## Tool Used

CircuitVerse

## Project Status

Completed
