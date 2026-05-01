# Dot Product & Orthogonality Check

## Description
This program calculates the **dot product** of two vectors and checks whether they are **orthogonal**.

Two vectors are orthogonal if their dot product equals **0**.

---

## Input
- `n`: number of vector pairs
- For each pair:
  - `m`: size of the vectors
  - `v1`: first vector of size `m`
  - `v2`: second vector of size `m`

---

## Output
For each vector pair:
- `"Orthogonal"` if dot product = 0  
- `"Not Orthogonal"` otherwise

---

## Algorithm

### Procedure: dot_product
1. Initialize `ps = 0`
2. For each index `i` from `0` to `n-1`:
   - Multiply `v1[i] * v2[i]`
   - Add result to `ps`
3. Return `ps`

---

### Main Algorithm
1. Read `n` (number of vector pairs)

2. Repeat for each pair:
   - Read `m` (size of vectors)
   - Input vector `v1`
   - Input vector `v2`
   - Call `dot_product(v1, v2, m, ps)`
   - If `ps == 0` → print "Orthogonal"
   - Else → print "Not Orthogonal"

---

## Formula
Dot Product:
