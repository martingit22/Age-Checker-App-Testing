# Age-Checker-App-Testing
Age Checker App Testing Repository  This repository contains test cases and documentation for the Age Checker App, demonstrating Equivalence Partitioning and Boundary Value Analysis techniques.

 Age Checker App Testing

## Equivalence Partitions:

### Valid Partitions:
- Children (less than 13): 0, 1, 5, 12
- Teenagers (13 to 19): 13, 15, 18, 19
- Adults (20 to 64): 20, 30, 50, 64
- Elders (65 and above): 65, 70, 80, 150

### Invalid Partitions:
- Negative Ages: -1, -5, -10
- Ages above 150: 151, 160, 200

## Boundary Values:

### Children:
- Lower Bound: 0
- Upper Bound: 12

### Teenagers:
- Lower Bound: 13
- Upper Bound: 19

### Adults:
- Lower Bound: 20
- Upper Bound: 64

### Elders:
- Lower Bound: 65
- Upper Bound: 150

### Invalid Ages:
- Lower Bound (Negative): -1
- Upper Bound (Above 150): 151

## Test Cases:

### Children:
- Test with age 0 (lower bound).
- Test with age 12 (upper bound).
- Test with age 6 (within the valid range).

### Teenagers:
- ...