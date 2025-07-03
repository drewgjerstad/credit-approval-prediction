# Credit Approval Prediction
This project focuses on predicting the outcome of credit card applications
based on variables collected during the application process. The dataset is
rather interesting since it is composed of several types of attributes. It was
sourced from the UCI Machine Learning Repository
([source](https://archive.ics.uci.edu/dataset/27/credit+approval)). In addition
to developing models to predict credit approval outcomes, there will also be an
emphasis on incorporating experiment tracking and code testing integrations
(i.e., Weights & Biases, MLflow, etc.). Note that, from source, all attribute
names and symbols (where applicable) have been changed to meaningless symbols to
protect data confidentiality.

Here is the BibTeX citation for the dataset:
```
@misc{credit_approval_27,
  author       = {Quinlan, J. R.},
  title        = {{Credit Approval}},
  year         = {1987},
  howpublished = {UCI Machine Learning Repository},
  note         = {{DOI}: https://doi.org/10.24432/C5FS30}
}
```

## Quick Links
 * Data Exploration Notebook


## Variable Information
 * `A1`: b, a.
 * `A2`: continuous.
 * `A3`: continuous.
 * `A4`: u, y, l, t.
 * `A5`: g, p, gg.
 * `A6`: c, d, cc, i, j, k, m, r, q, w, x, e, aa, ff.
 * `A7`: v, h, bb, j, n, z, dd, ff, o.
 * `A8`: continuous.
 * `A9`: t, f.
 * `A10`: t, f.
 * `A11`: continuous.
 * `A12`: t, f.
 * `A13`: g, p, s.
 * `A14`: continuous.
 * `A15`: continuous.
 * `A16`: +, -. (class attribute)
   - `+`: 307 (44.5%)
   - `-`: 383 (55.5%)