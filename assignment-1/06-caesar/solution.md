# Solution notes: Caesar cipher

## Approach

I check each character in the input. If it is a lowercase or uppercase letter, I shift it inside the alphabet. If it is not a letter, I leave it unchanged. I use the constant alphabet and wrap around when the shift goes past the end of the alphabet.

## Edge cases handled

- Empty input returns an empty string.
- Zero shift leaves the text unchanged.
- Negative and large shifts still work because of wrapping.
- Non-letter characters stay the same.

## Anything special

The wrap-around is handled with modulo, which keeps the code short.
