# Characters used and their meaning in RegEx.

`corpus` means collection of textual documents.

`r` actually means raw string

`$` (Dollar) is always added at the end of a string.

`^` (carot) used to mark the starting letters of a string

`.` (wildcard) denotes a character which can be literally anything.

`?` denotes that the character just before "?" is optional. The word shall be included in with or without the character placed just before "?".

`|` (pipe) and `[ ]` stands for "or". For e.x. `(g|h|i) = [ghi]`

`+` check for the occurance of character for one or more than one times.

`*` check for the occurance of character for zero or more than one times.

`\` helps a character to be recognized as a normal character of the string. Ex. on line 51 and 56

`{ }` tells the number of characters, for the expression just before "{ }", the string should consist of.

`?:` makes the expression include all the characters coming before the patter, in the string.

## Some common shortcuts

`\d` any digit lying between 0-9

`\D` any non digit character

`\s` any wide space character