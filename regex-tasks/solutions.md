## Sugestions

NB. There are several possibles answers for each problem. Here I proposed what I considered a robust solution.


### Task 1
We look for accented characters and other special characters not available in English.

- Find: `_(.*[áéóíúâêôîûàèòìùëïüçñ].*?)_`
- Replace: `{$1}`

### Task 2
- Find: `\[\d+\]`
- Replace: *leave empty*

### Task 3
- Find: `^\s*CHAPTER\s+([IVXLCDM]+)\s*$`
- Replace: `[$1]`

### Task 4
1. `[A-Z][a-z]{3,}ly`
2. ([A-Za-z]+-)+[A-Za-z]+

### Task 5
1. We replace the white-spaces with a new line:
	- Find: `\s+`
	- Replace: `\n`
2. We add a new line before the punctuation marks that are attached to the end of a word:
	- Find: `([\)\].,?!;:”"…])`
	- Replace: `\n$1`
2. We add a new line before the punctuation marks that are attached to the begining of a word:
	- Find: `([\(\[“"])`
	- Replace: `$1\n`
4. We delete any superfluous newlines (this is, empty new lines):
	- Find: `\n\s*\n`
	- Replace: `\n`

