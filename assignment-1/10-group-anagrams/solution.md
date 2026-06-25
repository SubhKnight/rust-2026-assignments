# Solution notes: Group anagrams

## Approach

I make a signature for each word by lowercasing it, sorting its letters, and joining them back together. Words with the same signature are anagrams, so I put them in the same group.

## Edge cases handled

- Empty input returns an empty list.
- Words with different lengths do not get grouped together.
- The original word casing is preserved in the output.

## Anything special

This solution is simple because the sorted letters form a good key for grouping.
