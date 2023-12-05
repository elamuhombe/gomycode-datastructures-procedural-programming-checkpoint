# Readme

## Problem 1: Sum of Distinct Elements from Two Sets

### Description
This algorithm calculates the sum of distinct elements from two sets. The sets are represented as arrays of integers.
The program algorithm is saved in sum-of-distinct-elements.algo file

### Procedure
- `sum_of_distinct_elements(set1, set2, result)`
    - Inputs:
        - `set1`: Array of integers representing the first set.
        - `set2`: Array of integers representing the second set.
    - Output:
        - `result`: Integer variable storing the sum of distinct elements from both sets.

### Example Usage
VAR
    set1, set2: ARRAY_OF_INTEGERS;
    sumResult: INTEGER;

BEGIN
    set1 := [3, 1, 7, 9];
    set2 := [2, 4, 1, 9, 3];

    sum_of_distinct_elements(set1, set2, sumResult);
    // Output: 13 (distinct elements 4, 7, 2)
END.

# Problem2: Dot Product and Orthogonality Check

## Problem Description

The algorithm fulfills the following:

### Dot Product Procedure

#### Procedure Name: `dot_product`

- **Description:**
  - Calculates the dot (scalar) product of two vectors, `v1` and `v2`, where both `v1` and `v2` are arrays of real numbers.
  - The procedure is stored in Dot-product.algo file.

- **Parameters:**
  - `v1`: Array of real numbers representing the first vector.
  - `v2`: Array of real numbers representing the second vector.
  - `ps`: Variable to store the dot product result.

- **Example Usage:**
  VAR
      vector1, vector2: ARRAY_OF_REAL;
      dotResult: REAL;

  BEGIN
      dot_product(vector1, vector2, dotResult);
      // dotResult now contains the dot product of vector1 and vector2
  END.

