# stock-count
the stock count of Selin's warehouse: every product, with its number.

## the count 
- the count lives in `count.txt`.
- one product per line: a name, one space, a number.
- new products go at the end of the file.

## how to change it
1. open an issue.
2. make a branch
3. commit, push, and open a pull request.
4. somebody else reviews it before it is merged.

The same steps as a diagram: [docs/workflow.md](docs/workflow.md).

## who does what

| who  | what                                 |
| -----| --------------------------------     |
| Selin| owns the count, merges pull requests |
| Kaan | counts, reviews pull requests        |

## read the history

Every line of the count has a commit behind it: 

```
git log  --oneline count.txt
git blame count.txt
```

 
## Decisions

- [0001 - The count is a plain text file](docs/adr/0001-plain-text-count.md)
