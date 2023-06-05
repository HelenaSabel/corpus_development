## Practical exercises

### Task 1
_To be carried out with the instructor’s assistance_

In the file `social-significance-drama_emma-goldman.txt`, there is pseudo-markup to indicate certain formatting information. In particular, underscores are used to delimit strings in italics (e.g. `_string_`). Semantically, we can see that there are three main uses of italics: character names, emphasis, foreign words. 
1. Look for strings delimited by underscores that contain accents, to find (at least some of) the foreign words. Replace the underscores of these words with `{string}`
2. Look for strings delimited by underscores that begin with a capital letter to detect the characters’ names. Replace the underscores of these words with angle brackets `<string>`

### Task 2
In the file `woman-church-state_matilda-gage.txt`, replace all the footnotes references (numbers between square brackets, e.g. `[8]`).

### Task 3
In the file `emmeline-orphan-castle_charlotte-smith.txt`, replace all the chapter headings (e.g. `CHAPTER I`) with just the Roman numeral between square brackets (this is, `[I]`). To be sure that it is a heading, your regular expression should check that there is no other content in the line.

### Task 4
In the file `galicia_meakin.txt`:
1. Find a word, at least 6 letters long, that ends in `ly` and starts with a uppercase letter (e.g. _Happily_)

2. Look for hyphenated words (e.g. _up-to-date_)

### Task 5
Transform the file `mrs-dalloway_woolf.txt`, so that it contains one token per line. You will need to do a series of regex manipulations (not just one expression).


## Sources

These files were taken from:

- `emmeline-orphan-castle_charlotte-smith.txt`. Project Gutenberg. Link: https://www.gutenberg.org/ebooks/41646 (this is a modified version of the Plain Text UTF-8 file)
- `social-significance-drama_emma-goldman.txt`. Project Gutenberg. Link: https://www.gutenberg.org/ebooks/43490 (this is a modified version of the Plain Text UTF-8 file)
- `woman-church-state_matilda-gage.txt`. Wikisource. Link: https://en.wikisource.org/wiki/History_of_Woman_Suffrage/Volume_1/Chapter_15 
- `galicia_meakin.txt`. Project Gutenberg.
- `mrs-dalloway_woolf.txt`. WikiSource.


## To finish on a happy note

[xkcd comic strip](https://xkcd.com/208/)
