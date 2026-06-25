# Solution notes: Longest word slice

## Approach

I split the sentence into words using whitespace. Then I check each word and keep the longest one seen so far. If there is a tie, I keep the first one because I only update when the new word is longer.

## Edge cases handled

- Empty or whitespace-only input returns None.
- A single word returns that word.
- Leading and trailing spaces are ignored.

## Anything special

This solution returns a borrowed slice, so it does not create a new String.
