# Solution notes: Split and double

## Approach

I split the vector into two mutable parts at the middle point. Then I double every number in each part. This works because Rust lets me borrow the two parts separately.

## Edge cases handled

- Midpoint zero gives an empty left part.
- Midpoint equal to the length gives an empty right part.
- Empty vectors are handled safely.
- A panic happens if the midpoint is larger than the length.

## Anything special

The important idea is using split-at-mut so the two borrows stay separate.
