# Practice: answer key

This folder holds the **reference answers**. Try a dataset yourself in `myself/` before opening the matching notebook here.

## How a round works

1. You finish a chapter and say which topic or domain you want to practise.
2. Claude picks two datasets:
   - **Clean**: loads straight into Python and fits the chapter notebook's steps almost one to one.
   - **Messy (real world)**: needs preprocessing before the chapter's steps apply.
3. Claude adds the answer notebooks here and a preprocessing starter in `myself/`.
4. You do both datasets in `myself/`, then commit and push.
5. Claude reviews your work against the answers. The review looks at whether your steps make sense and your final results are good enough, not whether your code looks like Claude's.

## Naming

Each chapter gets its own subfolder, and each dataset gets two files:

```
practice/<NN>_<chapter>/
    <NN>_clean_<dataset>_answer.ipynb   # chapter steps + the full answer on the clean dataset
    <NN>_messy_<dataset>_answer.ipynb   # preprocessing + the full answer on the messy dataset
```

If you ask for more datasets for the same chapter, they go in the same subfolder under new dataset names.

## Log

| Chapter | Topic you asked for | Clean dataset | Messy dataset | Status |
|---|---|---|---|---|
| | | | | |
