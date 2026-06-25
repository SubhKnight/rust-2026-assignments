# Solution notes: Reverse the word order

## Approach

I split the sentence into words, reverse the order of the words, and then join them back together with a single space. This automatically removes extra whitespace and trims the output.

## Edge cases handled

- Empty input returns an empty string.
- Whitespace-only input returns an empty string.
- Multiple spaces and tabs are cleaned up.

## Anything special

This is a short solution because Rust already gives us good tools for splitting and joining strings.
