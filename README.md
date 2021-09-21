# The paper

https://github.com/cscherrer/Soss-probprog/blob/master/paper/paper.pdf

# Citing

```
@proceedings{scherrer_chad_2020_5520061,
  title        = {{Soss: Declarative Probabilistic Programming via 
                   Runtime Code Generation}},
  year         = 2020,
  publisher    = {Zenodo},
  month        = oct,
  doi          = {10.5281/zenodo.5520061},
  url          = {https://doi.org/10.5281/zenodo.5520061}
}
```

# To Build
This requires [pygments-julia](https://github.com/sisl/pygments-julia)

Then, from the `paper/` directory, run
```
 latexmk -shell-escape -bibtex -pdf paper.tex
 ```
