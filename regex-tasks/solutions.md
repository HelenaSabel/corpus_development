## Sugestions

NB. There are several possibles answers for each problem. Here I proposed what I considered a robust solution.


### Task 1
We look for accented characters and other special characters not available in English.

- Find: `_(.*[áéóíúâêôîûàèòìùëïüçñ].*?)_`
- Replace: `{$1}`

### Task 2
- Find: `\[\d+\]`
- Replace: 

### Task 3
- Find: `^\s*CHAPTER\s+([IVXLCDM]+)\s*$`
- Replace: `[$1]`

### Task 4
1. `[A-Z][a-z]{3,}ly`
2. ([A-Za-z]+-)+[A-Za-z]+

### Task 5
In the file

