# 2-to-4 Decoder

A 2-to-4 decoder digital circuit simulation created using CircuitVerse.

## Inputs

- A
- B

## Outputs

- Y0
- Y1
- Y2
- Y3

## Working

A 2-to-4 decoder converts 2 binary inputs into 4 unique outputs.

Only one output is HIGH (1) for each input combination.

## Truth Table

| A | B | Y0 | Y1 | Y2 | Y3 |
|---|---|----|----|----|----|
| 0 | 0 | 1  | 0  | 0  | 0  |
| 0 | 1 | 0  | 1  | 0  | 0  |
| 1 | 0 | 0  | 0  | 1  | 0  |
| 1 | 1 | 0  | 0  | 0  | 1  |

## Boolean Expressions

Y0 = NOT A AND NOT B

Y1 = NOT A AND B

Y2 = A AND NOT B

Y3 = A AND B

## Real-Life Application

The decoder can be used for floor selection in an elevator.

- 00 → Ground Floor      
- 01 → 1st Floor
- 10 → 2nd Floor
- 11 → 3rd Floor

## Tool Used

CircuitVerse

## Status

Completed
