# Solution notes: Character frequency, sorted

## Approach

I count how many times each character appears using a hash map. After counting, I turn the map into a vector and sort it. I sort by count first, and if two characters have the same count, I sort them alphabetically.

## Edge cases handled

- Empty input returns an empty list.
- Single characters work normally.
- Spaces are counted too.

## Anything special

This solution is easy to understand because the counting part is very direct.
