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
In the file `galicia_meakin.txt`:
1. `[A-Z][a-z]{3,}ly`
2. ([A-Za-z]+-)+[A-Za-z]+


## Sources

These files were taken from:

- `emmeline-orphan-castle_charlotte-smith.txt`. Project Gutenberg. Link: https://www.gutenberg.org/ebooks/41646 (this is a modified version of the Plain Text UTF-8 file)
- `social-significance-drama_emma-goldman.txt`. Project Gutenberg. Link: https://www.gutenberg.org/ebooks/43490 (this is a modified version of the Plain Text UTF-8 file)
- `woman-church-state_matilda-gage.txt`. Wikisource. Link: https://en.wikisource.org/wiki/History_of_Woman_Suffrage/Volume_1/Chapter_15 
- `galicia_meakin.txt`. Project Gutenberg.


## To finish on a happy note

[xkcd comic strip](https://xkcd.com/208/)
