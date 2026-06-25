# Solution notes: `min_max`

## Approach

I start with the first value as both the minimum and maximum. Then I loop through the rest of the slice and update the values whenever I find a smaller or larger number.

## Edge cases handled

- Empty slices return None.
- Single-element slices return that element as both min and max.
- Negative numbers are handled correctly.

## Anything special

This solution follows the rule of not using iterator helpers.
