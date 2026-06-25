# Solution notes: Run-length encode

## Approach

I read the string one character at a time. I keep track of the current character and how many times it appears in a row. When the character changes, I save the finished group and start a new one.

## Edge cases handled

- Empty input returns an empty list.
- A single character returns one group.
- Spaces are treated like normal characters.

## Anything special

This is a simple loop-based solution. It does not need any advanced features.
