# belief-horn-merging-operators
This repository privdes an interactive example of the `belief-horn-merging-operators`.

## Interactive Example
The provided example has the following decisions:
```
reject
borderline
regular
accepted
```

The following reviews from 4 reviewers (in comma-separated values):
```
reviewer,paper,decision
1, 1, regular
1, 2, reject-borderline
2, 1, reject-borderline-regular
2, 2, regular-accepted
3, 3, accepted
3, 4, borderline
4, 3, regular-accepted
4, 4, borderline
```

And the following constraints:
```
Cada revisor ha d'avaluar, com a mímin, un article com a `accepted` o `regular`
```

## Try it
You can run the notebook directly from Google Colab
<a target="_blank" href="https://colab.research.google.com/github/danirivas/belief-horn-merging-operators/blob/main/review_process.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Citation
If you use this work, please cite our manuscript:
> Dellunde, Pilar and Costa, Vicent and Rivas-Barragan, Daniel. Belief Horn merging operators: characterization results
and implementations. Manuscript under review. 2023.
