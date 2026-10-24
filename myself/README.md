# Myself: your own attempts

Your own work goes here. The layout matches `practice/`:

```
myself/<NN>_<chapter>/
    <NN>_clean_<dataset>.ipynb                  # your attempt on the clean dataset
    <NN>_messy_<dataset>_preprocessing.ipynb    # starter from Claude: preprocessing snippets for the messy dataset
    <NN>_messy_<dataset>.ipynb                  # your attempt on the messy dataset (or keep going in the starter)
```

## Before you ask for a review

- **Run every cell and save the notebook with its outputs.** The review uses your printed scores and plots, so a notebook saved without outputs can't be reviewed properly.
- **Commit and push** to the branch you share with Claude. Claude can only read what has been pushed.
- Then ask, e.g.: "check my chapter 3 clean attempt".

## What the review looks at

- **Steps:** whether your workflow makes sense, e.g. you split the data before looking at it, you used cross-validation, and you picked a metric that suits the problem.
- **Results:** whether your final numbers are in a reasonable range compared with the answer key.
- **If your results are way off,** Claude will name the specific notebook in `practice/` to compare against, instead of rewriting your code.
