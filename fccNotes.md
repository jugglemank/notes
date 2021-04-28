regular expressions
test method- .test() test if a part of a string is present in a string
OR operator- | tests for a string OR another string
flags: g, or global, finds all. i ignores case. a period (.) is a wildcard. hu. returns hug, hum, huh, etc. plus sign, or +, checks to see if the char is one or more times. asterisk, \*, checks if something occurs zero or more times
caret symbol, ^, creates a negated char set. [^dku] would return all char not dku
character classes- /b[aiu]g/ would return big bag bug, but not bog or beg
define a group of characters you want to match by placing inside []
built in [letter-letter] range for the alphabet
also works for numbers.
for mixed values, letters first, then numbers, with no spaces all in one bracket set
greedy vs lazy matching
greedy finds the longest possible part of a string that fits the regex pattern
lazy finds the smallest ""
denoted with a ?
