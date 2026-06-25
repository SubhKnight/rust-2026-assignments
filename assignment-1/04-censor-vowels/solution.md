# Solution notes: Censor vowels in place

## Approach

I go through each character in the string. If the character is a vowel, I add `*` to a new string. If it is not a vowel, I keep the original character. At the end, I replace the old string with the new one.

## Edge cases handled

- Empty input stays empty.
- Uppercase and lowercase vowels are both changed.
- Non-vowel characters are left unchanged.

## Anything special

The function changes the string in place by replacing it with a rebuilt version.
