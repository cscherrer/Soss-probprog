# The paper

https://github.com/cscherrer/Soss-probprog/blob/master/paper/paper.pdf

# Citing

```
@inproceedings{scherrer2020soss, 
  title={Soss: Declarative Probabilistic Programming via Runtime Code Generation}, 
  DOI={10.5281/zenodo.5520061}, 
  abstractNote={0 <p>We present Soss, a declarative probabilistic programming language embedded in the Julia language. Soss represents statistical models in terms of abstract syntax trees, and uses staged compilation for on-demand generation of ``inference primitives&#39;&#39; (random sampling, log-density, etc) without requiring casual users to worry about such details.</p> <p>&nbsp;</p> <p>The approach taken by Soss makes it easy to extend to take advantage of other packages in the rapidly-growing Julia ecosystem. At the time of this writing, Soss users can choose from several inference back-ends and connect easily with larger systems SymPy and Gen.</p>}, 
  publisher={Zenodo}, 
  author={Scherrer, Chad and Zhao, Taine}, 
  year={2020}, 
  month={Oct} 
}
```

# To Build
This requires [pygments-julia](https://github.com/sisl/pygments-julia)

Then, from the `paper/` directory, run
```
 latexmk -shell-escape -bibtex -pdf paper.tex
 ```
