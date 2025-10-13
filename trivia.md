print(f'string{var}') print a string
print(f"{varname=}") is a shortcut to print varname=value

i can do this (xenc @ W)[3,13] and treat those inside () as one variable without a name

logits = log count.

.append() always adds the whole thing as one element.

if a is a tensor, a.storage() shows how a is stored in memory. a.view(2,3) does not change a.storage(), that's its advantage.

after logits add/subtract a constant the prob remains the same.

# self Q&A

Q1. the paper embed words. in this project we still use character level. do we embed or still use a-z to 1-26?

A1. we use embedding. instead of using 30-length vector to represent 17000 words, we use 2-length vector to represent 27 characters.  so C is 27 by 2 lookup table.
