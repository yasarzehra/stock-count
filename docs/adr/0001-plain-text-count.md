## context 

the auditors need to see every change to the count: which line, who, when, why.
git shows changes line by line, but only in text files. an excel file is a 
binary file: git can only say that it changed, not what changed. 

## decision 

the count is one plain text file, `count.txt` , with one product per line.

## consequences

- every change shows as a line in the history, and two people can change
different lines at the same time.
- no formulas: a total has to be computed by hand or with a command. 
 
## decisions 
- [0001 - the count is a plain text file](docs/adr/0001-plain-text-count.md) 
